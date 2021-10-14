tests:
	pytest tests

formatting:
	black {{cookiecutter.project_name}}/
	isort {{cookiecutter.project_name}}/

notebook-sync:
	jupytext --sync  notebooks/*.ipynb


clean_log:
	rm -rf lightning_logs

tensorboard:
	tensorboard --logdir ./lightning_logs
