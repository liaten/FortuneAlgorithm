## Требования:
- SFML
- cmake
- linux (preferable)
## Сборка проекта:
```bash
cd $HOME
mkdir -p $HOME/src
cd src
git clone https://github.com/liaten/FortuneAlgorithm
cd FortuneAlgorithm
cmake . && make -j$(nproc+1) && ./Fortune
```