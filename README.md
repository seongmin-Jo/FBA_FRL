# FBA_Finance_Reinforcement_Learning
## FRL session of FBA Quant 

1. First Setting

<pre>
<code>
$ python3 −m venv fba_frl
$ source fba_frl/bin/activate
or 
$ conda create -n fba_frl -python==3.7
$ conda activate fba_frl

(fba_frl) $ git config --global user.name <your_name>
(fba_frl) $ git config --global user.email <your_email>

(fba_frl) $ git clone https://github.com/seongmin-Jo/FBA_FRL.git
(fba_frl) $ cd FBA_FRL
(fba_frl) $ pip install matplotlib
(fba_frl) $ pip install -r requirements.txt
(fba_frl) $ pip install -e .
</code>
</pre>

2. Push Setting
<pre>
<code>
$ echo "# FBA Finance reinforcement learning" >> README.md
$ git init
$ git add .
$ git commit -m "<commit>"
$ git branch -M main
$ git remote add origin https://github.com/seongmin-Jo/FBA_FRL.git
$ git push -u origin main
</code>
</pre>



3. Pull Setting
<pre>
<code>
$ git remote add origin https://github.com/seongmin-Jo/FBA_FRL.git
$ git branch -M main
$ git push -u oriqin main
</code>
</pre>
