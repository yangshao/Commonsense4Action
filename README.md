Data for [Commonsense Justification for Action Explanation](http://aclweb.org/anthology/D18-1283) by  Shaohua Yang, Qiaozi Gao, Sari Saba-Sadiya and 
Joyce Y. Chai, EMNLP 2018.

The json file contains the training/validtion/testing samples
Each line contains one smaple and each sample object contains following properties:
- img_id: corresponding image id in visual genome dataset
- target_action: the groundtruth action
- relation_dic: a list of relations 
- attribute_dic: a list of attributes

Relation:
  - rel_id: id for the relation
  - subj: subject
  - obj: object
  - predicate: predicate
  - normed_subj: normalized subject
  - normed_obj: normalized object
  - normed_pred: normalized predicate
  - gd_flag: evidence flag
  
Attribute:
  - att_id: id for the attribute
  - obj: object
  - props: a list of properties
  - normed_obj: normalized object
  - normed_props: normalized properties
  - gd_flag:  evidence flag

## Citation
@inproceedings{yang2018commonsense,  
  title={Commonsense Justification for Action Explanation},   
  author={Yang, Shaohua and Gao, Qiaozi and Sadiya, Sari and Chai, Joyce},  
  booktitle={Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing},  
  pages={2627--2637},  
  year={2018}  
}  
