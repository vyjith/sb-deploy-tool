# This is for just demo for test-deploy command

```
git clone https://github.com/vyjith/test-deploy-tool.git
```
```
cd test-deploy-tool
```
```
chmod +x j.sh
```
```
echo "alias test-deploy='bash $(pwd)/j.sh'" >> ~/.bashrc
```
```
source ~/.bashrc
```
### Configure aws configure
```
aws configure
```
### After this click on the view push command option on Amazon ECR and then new window will open from there, copy the first command and login.

#### The execute the following command.

```
test-deploy ansiblestest -it
```
