import turtle

# Fungsi untuk menulis teks
def write_text():
    turtle.penup()
    turtle.goto(0, 0)
    turtle.color("blue")
    turtle.write("Selamat Belajar!", align="center", font=("Arial", 24, "normal"))

# Fungsi untuk menggambar animasi
def draw_animation():
    turtle.clear()
    write_text()

    # Animasi lainnya bisa ditambahkan di sini
    # Contoh: turtle.forward(100), turtle.right(90), dll.

    turtle.update()

# Atur tampilan awal
turtle.speed(1)
turtle.hideturtle()
write_text()

# Atur animasi berulang setiap 2 detik
turtle.ontimer(draw_animation, 2000)

# Jalankan loop utama
turtle.mainloop()

  

