def tanya_tampan():
    while True:
        print("Menurutmu, apakah aku tampan? (iya/tidak)")
        jawaban = input("Jawaban: ").strip().lower()

        if jawaban == "iya":
            print("Aku sudah menduganya!")
            break  # Keluar dari loop jika jawabannya "iya"
        elif jawaban == "tidak":
            print("Error: Maaf, coba lagi.")
        else:
            print("Input tidak valid. Silakan jawab 'iya' atau 'tidak'.")

if __name__ == "__main__":
    tanya_tampan()
