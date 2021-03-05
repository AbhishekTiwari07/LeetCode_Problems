class Solution {
public:
    vector<double> averageOfLevels(TreeNode* root) {
        vector<double> avg;
        queue<TreeNode*> q;
        q.push(root);
        while(!q.empty()){
            long long sum=0,count=q.size();
            for(int i=0;i<count;i++){
                TreeNode * temp = q.front();
                q.pop();
                sum+=temp->val;
                if(temp->left != NULL)
                    q.push(temp->left);
                if(temp->right!=NULL)
                    q.push(temp->right);
            }
            avg.push_back((double)sum/(1.0*count));
        }
        return avg;
    }
};