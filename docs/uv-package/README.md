# Uv package manager

I have come to appreciate the speed and ease of using UV package manager

```shell
DESKTOP-VOC7DM3% curl -LsSf https://astral.sh/uv/install.sh | sudo sh
downloading uv 0.6.14 x86_64-unknown-linux-gnu
no checksums to verify
installing to /root/.local/bin
  uv
  uvx
everything's installed!
DESKTOP-VOC7DM3% uv version
uv 0.6.11
DESKTOP-VOC7DM3% pwd
/var/www
DESKTOP-VOC7DM3% uv init data-engineers-notebook
Initialized project `data-engineers-notebook` at `/var/www/data-engineers-notebook`
DESKTOP-VOC7DM3% cd data-engineers-notebook
DESKTOP-VOC7DM3% pwd
/var/www/data-engineers-notebook
DESKTOP-VOC7DM3% uv add numpy scikit-learn xgboost
Using CPython 3.11.9 interpreter at: /home/peter/.pyenv/versions/3.11.9/bin/python3.11
Creating virtual environment at: .venv
Resolved 8 packages in 15.47s
⠴ Preparing packages... (2/7)
scikit-learn ------------------------------ 1.56 MiB/12.87 MiB
numpy      ------------------------------ 1.70 MiB/15.67 MiB
scipy      ------------------------------ 1.62 MiB/35.89 MiB
xgboost    ------------------------------ 1.49 MiB/242.12 MiB
nvidia-nccl-cu12 ------------------------------ 1.59 MiB/278.15 MiB

```