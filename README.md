# Practicing
# jupyter-notebook:        服務名稱
#    container_name: jupyter-notebook    容器名稱
#    command: start-notebook.sh --NotebookApp.token=''   讓進入jupyter notebook的使用者無需輸入token
#    image: jupyter/datascience-notebook                 掛載的映象檔
#    ports:
#      - 8081:8888                                       將port為由預設的8888改成自己設定的8081
