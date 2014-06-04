# submodule使い方リポジトリ　親リポジトリ

このリポジトリはtesting_submodules.gitリポジトリを子供に持つ

git clone git@github.com:youske-miyakoshi-geeplus/testing_submodules.git
とかしてみてください。

直後には何もないimage_childは何も入っていないフォルダとなるため

git submodule init
git submodule update


また clone した直後は不確定なブランチとなっているためimage_childはどこかのブランチに切り替える
git checkout master


testing_submodules_child.git もgitリポジトリであるため
ブランチを設定し切り替えることができる。

cd image_child
git branch feature/20140601-test







