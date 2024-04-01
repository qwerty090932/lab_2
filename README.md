# lab_2
На основе анализа предметной области "Агенство по трудоустройству", были выделены следующие информационные объекты, которые необходимо хранить в базе данных:
1. Работодатель(company)
    - company_id
    - company_name
    - type_activiry
    - number_representative
2. Должность(post)
    - post_id
    - post_name

3. Вакансия (vacancy)
    - vacancy_id
    - company_id
    - post_id
    - education
    - salary
  
4. Сделка (deal)
    - deal_id
    - vacancy_id
    - candidate_id
    - deal_date
5. Кандидат (candidate)
    - candidate_id
    - condidate_name
    - birthday
    - post_id
