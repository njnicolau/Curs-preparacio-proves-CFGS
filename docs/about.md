El meu nom és Nicolau, sóc professor d'educació secundària

# Estudis
Enginyer tècnic en informàtica de gestió. Especialitat de xarxes.

# Aficcions
M'agrada molt catxarretxar amb qualsevol aparell electric.

Estic ara clavat investigant temes de domòtica i energia solar.

??? question "Quina és l'última modificació que he afegit al configuration.yaml de HA"

    ```yaml
        diaria_energia_importada:
            source: sensor.energia_importada
            name: Energia importada diaria
            cycle: daily
            tariffs:
            - alta
            - mitja
            - baixa
    ```

    Prova a afegir-te aquest meter al HA

??? question "Quina és la estructura d'un programa Python?"

    ```python
        import os
        def main():
            # Ací el teu codi en python
            print("Hol, mon!")

        if __name__ == "__main__":
            main()
    ```

    Copia i prova el teu codi a un IDE
