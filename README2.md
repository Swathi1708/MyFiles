Description of Files:

input datasets
  - source_data : Dataset shared by the client team.
  - ml_ready_data : Manually created relevances and synonyms for the dataset provided.
  - bigfix_description_promts : Prompts for the task generating description

output datasets
  - ml_ready_train : Train dataset post split into 80:20 (train:test)
  - ml_ready_test : Test dataset post split into 80:20 (train:test).

finetuning_datasets
  - train_final : Final train data appended to the latest train data
  - test_final :  Final test data appended to the latest test data


  dataset_src   
  ├── approach_1                
  ├── approach_2 
  ├── rectify_relevance
  ├── documentation    
  ├── batch_0
  ├── batch_1
  ├── batch_2
  ├── batch_3
  └── batch_4

  ├── input_dataset
  │   ├── ml_ready_data
  │   └── bigfix_description_prompts
  ├── output_dataset
  |   ├── ml_ready_train
  |   └── ml_ready_test
  |   ├── train_final
  |   └── test_final
  └── finetuning_dataset
      ├── train_final
      └── test_final
   
![Physics](https://github.com/Swathi1708/MyFiles/assets/153712903/83ee993b-47c0-4917-afa7-bb4d7275e6f0)


