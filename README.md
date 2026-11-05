
reponses = [
    "paris",      
    "8",          
    "****",       # réponse 2 - indice : un animal de maison
    "bleu",
    "****",       # réponse 4 - indice : notre planète
    "****"        # réponse 5 - indice : le nom d'un serpent
]

****("🎓 Bienvenue au Chatbot Quiz !")
print("Réponds avec un seul mot, sans majuscule.")

parties = *

while ****:
    score = *
    parties = parties + 1
    print("\n--- Partie", parties, "---")

    reponse = *****("Quelle est la capitale de la France ? ").lower().*****()
    if reponse == reponses[0]:
        print("✅ Bravo !")
        score = score + 1
    ****:
        print("❌ Non, la réponse était", reponses[0])

    reponse = input("Combien font 5 + 3 ? ").strip()
    if reponse == reponses[*]:
        print("✅ Bravo !")
        score = ***** + 1
    else:
        print("❌ Non, la réponse était", reponses[1])

    reponse = input("Quel animal fait miaou ? ").lower().strip()
    if reponse == reponses[2]:
        print("✅ Bravo !")
        score = score + 1
    else:
        print("❌ Non, la réponse était", reponses[2])

    reponse = input("De quelle couleur est le ciel ? ").lower().strip()
    if reponse == reponses[*]:
        print("✅ Bravo !")
        score = score + 1
    ****:
        print("❌ Non, la réponse était", reponses[3])

    reponse = input("Sur quelle planète vivons-nous ? ").lower().strip()
    if reponse == reponses[4]:
        print("✅ Bravo !")
        score = ***** + 1
    else:
        print("❌ Non, la réponse était", reponses[4])

    reponse = input("Quel langage de programmation apprenons-nous ? ").lower().strip()
    if reponse == reponses[5]:
        print("✅ Bravo !")
        score = score + 1
    else:
        print("❌ Non, la réponse était", reponses[*])

    print("\n--- RÉSULTAT ---")
    print("Ton score :", *****, "/ 6")

    if score == 6:
        print("🏆 Parfait !")
    elif score ** 4:
        print("👍 Très bien !")
    ****:
        print("💪 Continue, tu vas y arriver !")

    rejouer = input("Veux-tu rejouer ? (oui/non) ").lower().strip()
    if rejouer == "non":
        *****

print("Merci d'avoir joué ! Tu as fait", *******, "parties.")
