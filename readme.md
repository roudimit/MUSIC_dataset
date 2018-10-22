## MUSIC Dataset from Sound of Pixels

This repo contains the YouTube video IDs for the videos used in Sound of Pixels. Currently, the dataset is at version 1.0, although it will be updated later with more instruments. 
'MUSIC_solo_videos.json' contains the YouTube video IDs for the solo performances of each instrument listed in the paper.
'MUSIC_duet_videos.json' contains the YouTube video IDs for the duet performances listed in the paper.

Note: the distribution of videos in 'MUSIC_solo_videos.json' is slightly different than as reported in the paper. In this repository, there are total of 685 videos, with 536 solo videos and 149 duet videos (the paper reports 714 total videos, with 565 solos and 149 duets). The next release of the paper will have these updated numbers and an updated figure. Here is the distribution of the solo videos in the json file. 

[(u'flute', 48),
(u'acoustic_guitar', 56),
(u'accordion', 60),
(u'xylophone', 49),
(u'erhu', 53),
(u'tuba', 51),
(u'saxophone', 25),
(u'cello', 57),
(u'violin', 53),
(u'clarinet', 41),
(u'trumpet', 43)]

If you use the dataset or code from the project, please cite:
```bibtex
    @InProceedings{Zhao_2018_ECCV,
        author = {Zhao, Hang and Gan, Chuang and Rouditchenko, Andrew and Vondrick, Carl and McDermott, Josh and Torralba, Antonio},
        title = {The Sound of Pixels},
        booktitle = {The European Conference on Computer Vision (ECCV)},
        month = {September},
        year = {2018}
    }
```
