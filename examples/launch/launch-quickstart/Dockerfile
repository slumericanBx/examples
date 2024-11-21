FROM python:3.14.0a1
COPY . /src
WORKDIR /src
RUN pip install wandb torch torchvision --extra-index-url https://download.pytorch.org/whl/cpu
ENTRYPOINT [ "env", "python3", "train.py"]