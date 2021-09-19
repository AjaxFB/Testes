# Exercício python 3 com git flow de 7 branchs
## Crie um repositório no github
## Crie, utilize e disponibilize a branch de desenvolvimento develop
## Crie, utilize a branch de feature/soma
## Adicione no test/test_pytest.py o código abaixo e construa o main.py
```python
from main import sum_numbers_sequence
def test_check_sum_1():
    assert sum_numbers_sequence([0,1,2,3,5,8]) == 19
def test_check_sum_2():
    assert sum_numbers_sequence([.1,.2,.3,.4]) == 1
```
## Disponibilize a branch feature/soma de modo que o teste passe
## Atualize e disponibilize a branch develop a partir da nova feature
## Crie e utilize a branch de feature/divisao
## Adicione no test/test_pytest.py o código abaixo e construa o main.py
```python
from main import div_numbers_sequence
def test_check_div_1():
    assert div_numbers_sequence(10,2) == 5
def test_check_div_2():
    assert div_numbers_sequence(.5,.1) == 5
```
## Disponibilize a branch feature/divisao de modo que o teste passe
## Atualize e disponibilize a branch develop a partir da nova feature
## Crie e utilize a branch de release/0.1.0 
## Disponibilize a release/0.1.0 com as features soma e divisao
## Crie e utilize a branch de hotfix/soma_e_divisao
## Adicione no test/test_pytest.py o código abaixo
```python
def test_check_sum_3():
    assert sum_numbers_sequence([.1,.2]) == .3
def test_check_div_3():
    assert div_numbers_sequence(.3,.1) == 3
```
## Disponibilize a branch hotfix/soma_e_divisao de modo que o teste passe ( com README.md explicando o hotfix)
## Disponibilize a branch develop com o hotfix
## Disponibilize a branch release/0.1.1 com o hotfix
## Opcionalmente crie testes e um bugfix que resolva em definitivo o problema de precisão do float
## Envie o link do repositório público no issue do projeto (lembre-se de linkar seu linkedin)
