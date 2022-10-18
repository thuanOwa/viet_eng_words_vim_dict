# Vietnamese + English words data

- view raw:
  <https://raw.githubusercontent.com/thuanOwa/viet_eng_words_vim_dict/main/words>
- raw data, not cleaned
- English start from beginning to line `479827` continue Vietnamese to end file
- Vim using fzf complete word? copy the raw data to `/usr/share/dict/words`
- dataset source? -> some where in the internet

```bash
cd /usr/share/dict/
sudo mv words words.backup
sudo wget https://raw.githubusercontent.com/thuanOwa/viet_eng_words_vim_dict/main/words
cd -
```

**or**

```bash
mkdir ~/repos
cd ~/repos
git clone https://github.com/thuanOwa/viet_eng_words_vim_dict/
cd -
sudo ln -sf ~/repos/viet_eng_words_vim_dict/words /usr/share/words
```
