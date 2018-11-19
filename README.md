# Commonsense4Action
Data for [Commonsense Justification for Action Explanation](http://aclweb.org/anthology/D18-1283) by  Shaohua Yang, Qiaozi Gao, Sari Saba-Sadiya and 
Joyce Y. Chai, EMNLP 2018.

The pkl file contains the training/validtion/testing samples
Each sample object contains following properties:
- img_id: corresponding image id in visual genome dataset
- target_action: the groundtruth action
- relation_dic: a dictionary contains relation objects
- attribute_dic: a dictionary contains attribute objects

## Citation
@inproceedings{yang2018commonsense,
  title={Commonsense Justification for Action Explanation},
  author={Yang, Shaohua and Gao, Qiaozi and Sadiya, Sari and Chai, Joyce},
  booktitle={Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing},
  pages={2627--2637},
  year={2018}
}
