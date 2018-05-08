bootstrap: docker
FROM: r-base:3.3.1

%labels
AUTHOR Yasasvy Nanyam ynanyam@iastate.edu

%post

apt update

apt install -y python3.5 python3.5-dev curl git

curl "https://bootstrap.pypa.io/get-pip.py" -o "get-pip.py"

python3.5 get-pip.py

pip3 install --no-cache-dir https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.10.0rc0-cp35-cp35m-linux_x86_64.whl

pip3 install --no-cache-dir plasFlow
