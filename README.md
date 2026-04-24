# b\_mat\_1023\_numerik
## setup (linux)
vom root des projektes:
```bash
python3 -m venv .b_mat_1023_numerik
source .b_mat_1023_numerik/bin/activate
pip install -r requirements.txt
python3 -m ipykernel install --user \
       --name="b_mat_1023_numerik-kernel" \
       --display-name="b_mat_1023_numerik"
```

Daraufhin kann entweder der Jupyter Server gestartet werden oder die Datei ueber nvim geoffnet werden.
