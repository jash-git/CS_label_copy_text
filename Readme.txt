Ｃ# label copy text（Ｃ# label標籤文字複製選取）

資料來源：https://stackoverflow.com/questions/7748137/is-it-possible-to-select-text-on-a-windows-form-label

GITHUB: https://github.com/jash-git/CS_label_copy_text

TextBox1.Text = "Hello, Select Me";
TextBox1.ReadOnly = true;
TextBox1.BorderStyle = 0;
TextBox1.BackColor = this.BackColor;
TextBox1.TabStop = false;