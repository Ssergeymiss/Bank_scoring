# Bank_scorring
Рекомендации и предложения по изменению признакового пространства, использованию внешних данных и иному развитию базовой модели:
Согласно перекрестной проверки выдвигается гипотеза о том, что такие переменнные датасета как 'ratio_sum_outstanding_to_open_sum', 'ratio_overdue_loans_3_to_12','overdue_loans_3','ratio_pattern_len_to_pattern_2','ratio_pattern_len_to_pattern_3', 'ratio_pattern_len_to_pattern_4','close_loan_median',"is_lost_1","is_lost_3",'is_lost_12','is_lost_100','overdue_loans_12',
'ratio_history_100','ratio_history_12','ratio_history_3','overdue_loans_3', 'is_type_credit_card_1',
'is_active_type_credit_card_1'- не оказывают существенного влияния на точность модели машинного обучения
Следовательно, избавившись от необходимости измерять данные значения мы сэкономим память и затраты на обработку данных.
