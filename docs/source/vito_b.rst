.. _vito_b:


Primeiro Cenário do Jogo
========================

Vamos começar importando o módulo ameixa para criar um jogo baseado na biblioteca Vitollino.
 Neste módulo vamos usar a classe Cena, que vai permitir a criação da primeira cena, o lago das tartarugas:

.. image:: /_static/tartarugas.png

.. code-block:: python

    from _spy.vitollino.vitollino import Cena

    TARTARUGAS = "https://activufrj.nce.ufrj.br/studio/labase/lago.jpg?disp=inline&size=G"

    def main():
        uma_cena = Cena(img=TARTARUGAS)
        uma_cena.vai()

    if __name__ == "__main__":
        Jogo()

.. moduleauthor:: Carlo Oliveira <carlo@nce.ufrj.br>

.. note::
Ainda é um programa bem simples.
