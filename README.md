# Audio-visual stimuli representational similarity analysis (RSA) project for Cognitive Robotics Master's Dissertation 

## Experiment 
- [Multiple arrangements task](https://meadows-research.com/users/Taranks7/)

## Set up ## 
**Setting up the environment:**

```
cd Audio-visual_similarity 
# CREATE VIRTUAL ENVIRONMENT
# virtualenv venv -p python3
source venv/bin/activate
```
- The data are presumed to be at ~/Audio-visual_similarity
- Install dependencies: pip install -r requirements.txt

**Run**
```
python3 mp4.py #download youtube playlist and individual videos 
python3 process_mp4.py #process videos - cut, crop, scale, normalise sound, extract audio, extract image and save
```
