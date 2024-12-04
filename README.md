# test
error
Type "help", "copyright", "credits" or "license" for more information.        
>>> hoto": "kart.jpg", "country": "USA", "language": "English", "greeting": "Happy Birthday!", "flag": "usa_flag.jpg"},
  File "<stdin>", line 1
    hoto": "kart.jpg", "country": "USA", "language": "English", "greeting": "Happy Birthday!", "flag": "usa_flag.jpg"},
        ^^^^
SyntaxError: invalid syntax
>>>     {"name": "bhunf", "photo": "bhunf.jpg", "country": "China", "language": "简体中文", "greeting": "生日快樂 (Shēngrì kuàilè)", "flag": "china_flag.jpg"},
  File "<stdin>", line 1
    {"name": "bhunf", "photo": "bhunf.jpg", "country": "China", "language": " 简体中文", "greeting": "生日快樂 (Shēngrì kuàilè)", "flag": "china_flag.jpg"},
IndentationError: unexpected indent    
>>>     {"name": "indra", "photo": "indra.jpg", "country": "Indonesia", "language": " Bahasa Indonesia", "greeting": "Selamat ulang tahun!", "flag": "indonesia_flag.jpg"},
  File "<stdin>", line 1
    {"name": "indra", "photo": "indra.jpg", "country": "Indonesia", "language": " Bahasa Indonesia", "greeting": "Selamat ulang tahun!", "flag": "indonesia_flag.jpg"},
IndentationError: unexpected indent    
>>>     {"name": "bot", "photo": "bot.jpg", "country": "Thailand", "language": "ไทย ", "greeting": "สุขสันต์วันเกิด (    (S̄uk̄hs̄ạnt̒ wạn keid)", "flag": "thail   land_flag.jpg"},
  File "<stdin>", line 1
    {"name": "bot", "photo": "bot.jpg", "country": "Thailand", "language": "ไทย ", "greeting": "สุขสันต์วันเกิด (S̄uk     k̄hs̄ạnt̒ wạn keid)", "flag": "thailand_  _flag.jpg"},
IndentationError: unexpected indent    
>>>     {"name": "hans", "photo": "hans.jpg", "country": "Germany", "language": "Deutsch", "greeting": "Alles Gute zum Geburtstag!", "flag": "germany_flag.jpg"},
  File "<stdin>", line 1
    {"name": "hans", "photo": "hans.jpg", "country": "Germany", "language": "Deutsch", "greeting": "Alles Gute zum Geburtstag!", "flag": "germany_flag.jpg"},
IndentationError: unexpected indent    
>>>     {"name": "ji", "photo": "ji.jpg", "country": "South Korea", "language": "한국어", "greeting": "생일 축하해요 (Saeng-il chugha haeyo)", "flag": "south_korea_flag.jpg"},
  File "<stdin>", line 1
    {"name": "ji", "photo": "ji.jpg", "country": "South Korea", "language": " 한국어", "greeting": "생일 축하해요 (Saeng-il chugha haeyo)", "flag": "south_korea_flag.jpg"},
IndentationError: unexpected indent    
>>>     {"name": "wei", "photo": "wei.jpg", "country": "Taiwan", "language": "繁體中文", "greeting": "生日快樂 (Shēngrì kuàilè)", "flag": "taiwan_flag.jpg"},
  File "<stdin>", line 1
    {"name": "wei", "photo": "wei.jpg", "country": "Taiwan", "language": "繁體中文", "greeting": "生日快樂 (Shēngrì kuàilè)", "flag": "taiwan_flag.jpg"},   
IndentationError: unexpected indent    
>>>     {"name": "mei", "photo": "mei.jpg", "country": "Macau", "language": " 粵式中文", "greeting": "生日快樂 (Shēngrì kuàilè)", "flag": "macau_flag.jpg"}
  File "<stdin>", line 1
    {"name": "mei", "photo": "mei.jpg", "country": "Macau", "language": "粵式 中文", "greeting": "生日快樂 (Shēngrì kuàilè)", "flag": "macau_flag.jpg"}     
IndentationError: unexpected indent    
>>>     {"name": "dong", "photo": "dong.jpg", "country": "Netherlands", "language": "Dutch", "greeting": "Gefeliciteerd met je verjaardag!", "flag": "netherlands_flag.jpg"}
  File "<stdin>", line 1
    {"name": "dong", "photo": "dong.jpg", "country": "Netherlands", "language": "Dutch", "greeting": "Gefeliciteerd met je verjaardag!", "flag": "netherlands_flag.jpg"}
IndentationError: unexpected indent    
>>> ]
  File "<stdin>", line 1
    ]
    ^
SyntaxError: unmatched ']'
>>>
>>> # Sample options for languages
>>> language_options = ["Afrikaans", "English", "简体中文", "Bahasa Indonesia", "ไทย", "Deutsch", "한국어","繁體中文","粵式中文","Nederlands"]
>>>
>>> class GuessingGame:
...     def __init__(self, root):      
...         self.root = root
...         self.root.title("Guess the Country and Language Game")
...         self.root.geometry("600x700")
...         self.root.configure(bg="#ADD8E6")  # Change background color to light blue
...         
...         self.current_friend_index = 0
...         self.score = 0
...         self.selected_country = None
...         self.selected_language = None
...
...         self.engine = pyttsx3.init()  # 初始化语音引擎
...         
...         self.create_widgets()      
...
>>>     def create_widgets(self):
  File "<stdin>", line 1
    def create_widgets(self):
IndentationError: unexpected indent    
>>>         tk.Label(self.root, text="Fill out your name:", bg="#ADD8E6", font=("Helvetica", 12)).pack(pady=10)
  File "<stdin>", line 1
    tk.Label(self.root, text="Fill out your name:", bg="#ADD8E6", font=("Helvetica", 12)).pack(pady=10)
IndentationError: unexpected indent    
>>>         self.name_entry = tk.Entry(self.root, font=("Helvetica", 12))     
  File "<stdin>", line 1
    self.name_entry = tk.Entry(self.root, font=("Helvetica", 12))
IndentationError: unexpected indent    
>>>         self.name_entry.pack(pady=5)
  File "<stdin>", line 1
    self.name_entry.pack(pady=5)       
IndentationError: unexpected indent    
>>>
>>>         self.start_button = tk.Button(self.root, text="Start Game", command=self.start_game, bg="#4CAF50", fg="white", font=("Helvetica", 12))
  File "<stdin>", line 1
    self.start_button = tk.Button(self.root, text="Start Game", command=self.start_game, bg="#4CAF50", fg="white", font=("Helvetica", 12))
IndentationError: unexpected indent    
>>>         self.start_button.pack(pady=20)
  File "<stdin>", line 1
    self.start_button.pack(pady=20)    
IndentationError: unexpected indent    
>>>
>>>     def start_game(self):
  File "<stdin>", line 1
    def start_game(self):
IndentationError: unexpected indent    
>>>         self.player_name = self.name_entry.get()
  File "<stdin>", line 1
    self.player_name = self.name_entry.get()
IndentationError: unexpected indent    
>>>         if not self.player_name:
  File "<stdin>", line 1
    if not self.player_name:
IndentationError: unexpected indent    
>>>             messagebox.showwarning("Input Error", "Please enter your name to start the game.")
  File "<stdin>", line 1
    messagebox.showwarning("Input Error", "Please enter your name to start the game.")
IndentationError: unexpected indent    
>>>             return
  File "<stdin>", line 1
    return
IndentationError: unexpected indent    
>>>
>>>         self.start_button.pack_forget()
  File "<stdin>", line 1
    self.start_button.pack_forget()    
IndentationError: unexpected indent    
>>>         self.name_entry.pack_forget()
  File "<stdin>", line 1
    self.name_entry.pack_forget()      
IndentationError: unexpected indent    
>>>
>>>         self.condition_label = tk.Label(self.root, text="You need to get at least 70 points to win the prize :)", bg="#ADD8E6", font=("Helvetica", 12))
  File "<stdin>", line 1
    self.condition_label = tk.Label(self.root, text="You need to get at least 70 points to win the prize :)", bg="#ADD8E6", font=("Helvetica", 12))
IndentationError: unexpected indent    
>>>
>>>         self.condition_label.pack(pady=10)
  File "<stdin>", line 1
    self.condition_label.pack(pady=10) 
IndentationError: unexpected indent    
>>>
>>>         self.instructions_label = tk.Label(self.root, text="This game is d
esigned to test how well you know your ten friends (some of whom might be really close to you). You need to identify their nationalities and the languages they speak. If you get both answers correct, you earn 10 points; otherwise, you get 0 points. The goal is to score above 70 points to win a special gift. If you don't reach 70 points, you'll need to try again to show more affection towards your friends. Good luck!", bg="#ADD8E6", font=("Helvetica", 12), wraplength=500, justify="left")
  File "<stdin>", line 1
    self.instructions_label = tk.Label(self.root, text="This game is designed to test how well you know your ten friends (some of whom might be really close to you). You need to identify their nationalities and the languages they speak. If you get both answers correct, you earn 10 points; otherwise, you get 0 points. The goal is to score above 70 points to win a special gift. If you don't reach 70 points, you'll need to try again to show more affection towards your friends. Good luck!", bg="#ADD8E6", font=("Helvetica", 12), wraplength=500, justify="left")
IndentationError: unexpected indent    
>>>         self.instructions_label.pack(pady=10)
  File "<stdin>", line 1
    self.instructions_label.pack(pady=10)
IndentationError: unexpected indent    
>>>
>>>         self.root.after(5000, self.hide_initial_labels)  # 5秒后隐藏标签
  File "<stdin>", line 1
    self.root.after(5000, self.hide_initial_labels)  # 5秒后隐藏标签
IndentationError: unexpected indent    
>>>
>>>         self.title_label = tk.Label(self.root, text="", bg="#ADD8E6", font=("Helvetica", 16, "bold"))
  File "<stdin>", line 1
    self.title_label = tk.Label(self.root, text="", bg="#ADD8E6", font=("Helvetica", 16, "bold"))
IndentationError: unexpected indent    
>>>         self.title_label.pack(pady=10)
  File "<stdin>", line 1
    self.title_label.pack(pady=10)     
IndentationError: unexpected indent    
>>>
>>>         self.photo_label = tk.Label(self.root, bg="#ADD8E6")  # Change background color to light blue
  File "<stdin>", line 1
    self.photo_label = tk.Label(self.root, bg="#ADD8E6")  # Change background color to light blue
IndentationError: unexpected indent    
>>>         self.photo_label.pack(pady=20)
  File "<stdin>", line 1
    self.photo_label.pack(pady=20)     
IndentationError: unexpected indent    
>>>
>>>         tk.Label(self.root, text="Select Country:", bg="#ADD8E6", font=("Helvetica", 12)).pack()  # Change background color to light blue
  File "<stdin>", line 1
    tk.Label(self.root, text="Select Country:", bg="#ADD8E6", font=("Helvetica", 12)).pack()  # Change background color to light blue
IndentationError: unexpected indent    
>>>
>>>         self.flag_frame = tk.Frame(self.root, bg="#ADD8E6")
  File "<stdin>", line 1
    self.flag_frame = tk.Frame(self.root, bg="#ADD8E6")
IndentationError: unexpected indent    
>>>         self.flag_frame.pack(pady=5)
  File "<stdin>", line 1
    self.flag_frame.pack(pady=5)       
IndentationError: unexpected indent    
>>>
>>>         for friend in friends_data:

  File "<stdin>", line 1
    for friend in friends_data:        
IndentationError: unexpected indent    
>>>             flag_image = Image.open(friend["flag"])
  File "<stdin>", line 1
    flag_image = Image.open(friend["flag"])
IndentationError: unexpected indent    
>>>             flag_image = flag_image.resize((100, 60), Image.LANCZOS)      
  File "<stdin>", line 1
    flag_image = flag_image.resize((100, 60), Image.LANCZOS)
IndentationError: unexpected indent    
>>>             flag_photo = ImageTk.PhotoImage(flag_image)
  File "<stdin>", line 1
    flag_photo = ImageTk.PhotoImage(flag_image)
IndentationError: unexpected indent    
>>>             flag_button = tk.Button(self.flag_frame, image=flag_photo, command=lambda f=friend: self.select_country(f))
  File "<stdin>", line 1
    flag_button = tk.Button(self.flag_frame, image=flag_photo, command=lambda f=friend: self.select_country(f))      
IndentationError: unexpected indent    
>>>             flag_button.image = flag_photo
  File "<stdin>", line 1
    flag_button.image = flag_photo     
IndentationError: unexpected indent    
>>>             flag_button.pack(side=tk.LEFT, padx=10)
  File "<stdin>", line 1
    flag_button.pack(side=tk.LEFT, padx=10)
IndentationError: unexpected indent    
>>>
>>>         tk.Label(self.root, text="Select Language:", bg="#ADD8E6", font=("Helvetica", 12)).pack()  # Change background color to light blue
  File "<stdin>", line 1
    tk.Label(self.root, text="Select Language:", bg="#ADD8E6", font=("Helvetica", 12)).pack()  # Change background color to light blue
IndentationError: unexpected indent    
>>>
>>>         self.language_frame = tk.Frame(self.root, bg="#ADD8E6")
  File "<stdin>", line 1
    self.language_frame = tk.Frame(self.root, bg="#ADD8E6")
IndentationError: unexpected indent    
>>>         self.language_frame.pack(pady=5)
  File "<stdin>", line 1
    self.language_frame.pack(pady=5)   
IndentationError: unexpected indent    
>>>
>>>         for language in language_options:
  File "<stdin>", line 1
    for language in language_options:  
IndentationError: unexpected indent    
>>>             language_button = tk.Button(self.language_frame, text=language, command=lambda l=language: self.select_language(l), bg="#4CAF50", fg="white", font=("Helvetica", 10))
  File "<stdin>", line 1
    language_button = tk.Button(self.language_frame, text=language, command=lambda l=language: self.select_language(l), bg="#4CAF50", fg="white", font=("Helvetica", 10))
IndentationError: unexpected indent    
>>>             language_button.pack(side=tk.LEFT, padx=10)
  File "<stdin>", line 1
    language_button.pack(side=tk.LEFT, padx=10)
IndentationError: unexpected indent    
>>>
>>>         self.submit_button = tk.Button(self.root, text="Submit Guess", command=self.check_guess, bg="#4CAF50", fg="white", font=("Helvetica", 12))
  File "<stdin>", line 1
    self.submit_button = tk.Button(self.root, text="Submit Guess", command=self.check_guess, bg="#4CAF50", fg="white", font=("Helvetica", 12))
IndentationError: unexpected indent    
>>>         self.submit_button.pack(pady=20)
  File "<stdin>", line 1
    self.submit_button.pack(pady=20)   
IndentationError: unexpected indent    
>>>
>>>         self.greeting_label = tk.Label(self.root, bg="#ADD8E6", font=("Helvetica", 12))  # Label to display greeting in selected language
  File "<stdin>", line 1
    self.greeting_label = tk.Label(self.root, bg="#ADD8E6", font=("Helvetica", 12))  # Label to display greeting in selected language
IndentationError: unexpected indent    
>>>         self.greeting_label.pack(pady=5)
  File "<stdin>", line 1
    self.greeting_label.pack(pady=5)   
IndentationError: unexpected indent    
>>>
>>>         self.load_friend()
  File "<stdin>", line 1
    self.load_friend()
IndentationError: unexpected indent    
>>>
>>>     def load_friend(self):
  File "<stdin>", line 1
    def load_friend(self):
IndentationError: unexpected indent    
>>>         friend = friends_data[self.current_friend_index]
  File "<stdin>", line 1
    friend = friends_data[self.current_friend_index]
IndentationError: unexpected indent    
>>>
>>>         image = Image.open(friend["photo"])
  File "<stdin>", line 1
    image = Image.open(friend["photo"])
IndentationError: unexpected indent    
>>>         image = image.resize((250, 250), Image.LANCZOS)
  File "<stdin>", line 1
    image = image.resize((250, 250), Image.LANCZOS)
IndentationError: unexpected indent    
>>>         photo = ImageTk.PhotoImage(image)
  File "<stdin>", line 1
    photo = ImageTk.PhotoImage(image)  
IndentationError: unexpected indent    
>>>
>>>         self.photo_label.config(image=photo)
  File "<stdin>", line 1
    self.photo_label.config(image=photo)
IndentationError: unexpected indent    
>>>         self.photo_label.image = photo
  File "<stdin>", line 1
    self.photo_label.image = photo     
IndentationError: unexpected indent    
>>>
>>>         self.title_label.config(text=f"How much do you know about {friend['name']}?")
  File "<stdin>", line 1
    self.title_label.config(text=f"How much do you know about {friend['name']}?")
IndentationError: unexpected indent    
>>>
>>>     def select_country(self, friend):
  File "<stdin>", line 1
    def select_country(self, friend):  
IndentationError: unexpected indent    
>>>         self.selected_country = friend["country"]
  File "<stdin>", line 1
    self.selected_country = friend["country"]
IndentationError: unexpected indent    
>>>
>>>     def select_language(self, language):
  File "<stdin>", line 1
    def select_language(self, language):
IndentationError: unexpected indent    
>>>         self.selected_language = language
  File "<stdin>", line 1
    self.selected_language = language  
IndentationError: unexpected indent    
>>>
>>>     def check_guess(self):
  File "<stdin>", line 1
    def check_guess(self):
IndentationError: unexpected indent    
>>>         correct_country =  friends_data[self.current_friend_index]["country"]
  File "<stdin>", line 1
    correct_country =  friends_data[self.current_friend_index]["country"]     
IndentationError: unexpected indent    
>>>         correct_language = friends_data[self.current_friend_index]["language"]
  File "<stdin>", line 1
    correct_language = friends_data[self.current_friend_index]["language"]    
IndentationError: unexpected indent    
>>>         correct_greeting = friends_data[self.current_friend_index]["greeting"]
  File "<stdin>", line 1
    correct_greeting = friends_data[self.current_friend_index]["greeting"]    
IndentationError: unexpected indent    
>>>
>>>         if (self.selected_country == friends_data[self.current_friend_index]["country"] and
  File "<stdin>", line 1
    if (self.selected_country == friends_data[self.current_friend_index]["country"] and
IndentationError: unexpected indent    
>>>     self.selected_language == friends_data[self.current_friend_index]["language"]):
  File "<stdin>", line 1
    self.selected_language == friends_data[self.current_friend_index]["language"]):
IndentationError: unexpected indent    
>>>             messagebox.showinfo("Result", f"This is correct, Bao bao is so intelligent! {correct_greeting}")
  File "<stdin>", line 1
    messagebox.showinfo("Result", f"This is correct, Bao bao is so intelligent! {correct_greeting}")
IndentationError: unexpected indent    
>>>
>>>             self.greeting_label.config(text=correct_greeting)
  File "<stdin>", line 1
    self.greeting_label.config(text=correct_greeting)
IndentationError: unexpected indent    
>>>             self.score += 10
  File "<stdin>", line 1
    self.score += 10
IndentationError: unexpected indent    
>>>
>>>             # 使用语音引擎朗读生日
快乐
>>>             self.engine.say(correct_greeting)
  File "<stdin>", line 1
    self.engine.say(correct_greeting)  
IndentationError: unexpected indent    
>>>             self.engine.runAndWait()
  File "<stdin>", line 1
    self.engine.runAndWait()
IndentationError: unexpected indent    
>>>         else:
  File "<stdin>", line 1
    else:
IndentationError: unexpected indent    
>>>             messagebox.showinfo("Result", f"So sorry but the correct answer is {correct_country} and {correct_language}.")
  File "<stdin>", line 1
    messagebox.showinfo("Result", f"So sorry but the correct answer is {correct_country} and {correct_language}.")   
IndentationError: unexpected indent    
>>>         # 使用语音引擎朗读生日快乐 
>>>             self.engine.say(correct_greeting)
  File "<stdin>", line 1
    self.engine.say(correct_greeting)  
IndentationError: unexpected indent    
>>>             self.engine.runAndWait()
  File "<stdin>", line 1
    self.engine.runAndWait()
IndentationError: unexpected indent    
>>>
>>>         self.current_friend_index += 1
  File "<stdin>", line 1
    self.current_friend_index += 1     
IndentationError: unexpected indent    
>>>
>>>         if self.current_friend_index < len(friends_data):
  File "<stdin>", line 1
    if self.current_friend_index < len(friends_data):
IndentationError: unexpected indent    
>>>             self.load_friend()     
  File "<stdin>", line 1
    self.load_friend()
IndentationError: unexpected indent    
>>>             self.greeting_label.config(text="")
  File "<stdin>", line 1
    self.greeting_label.config(text="")
IndentationError: unexpected indent    
>>>             self.selected_language = None
  File "<stdin>", line 1
    self.selected_language = None      
IndentationError: unexpected indent    
>>>             self.selected_country = None
  File "<stdin>", line 1
    self.selected_country = None       
IndentationError: unexpected indent    
>>>         else:
  File "<stdin>", line 1
    else:
IndentationError: unexpected indent    
>>>             if self.score >= 70:
  File "<stdin>", line 1
    if self.score >= 70:
IndentationError: unexpected indent    
>>>                 messagebox.showinfo("GG Well Play", f" Your score is {self.score}/{len(friends_data) * 10}, You are so smarrrrt! Congrats, check this out!")
  File "<stdin>", line 1
    messagebox.showinfo("GG Well Play", f" Your score is {self.score}/{len(friends_data) * 10}, You are so smarrrrt! Congrats, check this out!")
IndentationError: unexpected indent    
>>>                 webbrowser.open("https://www.youtube.com/watch?v=dQw4w9WgXcQ")
  File "<stdin>", line 1
    webbrowser.open("https://www.youtube.com/watch?v=dQw4w9WgXcQ")
IndentationError: unexpected indent    
>>>             else:
  File "<stdin>", line 1
    else:
IndentationError: unexpected indent
>>>                 messagebox.showinfo("Game Over", f"Game Over! Your score is {self.score}/{len(friends_data) * 10}.")
  File "<stdin>", line 1
    messagebox.showinfo("Game Over", f"Game Over! Your score is {self.score}/{len(friends_data) * 10}.")
IndentationError: unexpected indent    
>>>                 play_again = messagebox.askyesno("Play Again?", "Your score is below 70. Do you want to try again?")
  File "<stdin>", line 1
    play_again = messagebox.askyesno("Play Again?", "Your score is below 70. Do you want to try again?")
IndentationError: unexpected indent    
>>>             if play_again:
  File "<stdin>", line 1
    if play_again:
IndentationError: unexpected indent    
>>>                 self.reset_game()
  File "<stdin>", line 1
    self.reset_game()
IndentationError: unexpected indent    
>>>             else:
  File "<stdin>", line 1
    else:
IndentationError: unexpected indent    
>>>                 self.root.quit()
  File "<stdin>", line 1
    self.root.quit()
IndentationError: unexpected indent    
>>>
>>>     def reset_game(self):
  File "<stdin>", line 1
    def reset_game(self):
IndentationError: unexpected indent    
>>>         self.current_friend_index = 0
  File "<stdin>", line 1
    self.current_friend_index = 0      
IndentationError: unexpected indent    
>>>         self.score = 0
  File "<stdin>", line 1
    self.score = 0
IndentationError: unexpected indent    
>>>         self.selected_country = None
  File "<stdin>", line 1
    self.selected_country = None       
IndentationError: unexpected indent    
>>>         self.selected_language = None
  File "<stdin>", line 1
    self.selected_language = None      
IndentationError: unexpected indent    
>>>         self.load_friend()
  File "<stdin>", line 1
    self.load_friend()
IndentationError: unexpected indent    
>>>         
>>> if __name__ == "__main__":
...     root = tk.Tk()
...     game = GuessingGame(root)      
...     root.mainloop()
...
Traceback (most recent call last):     
  File "<stdin>", line 2, in <module>  
NameError: name 'tk' is not defined
