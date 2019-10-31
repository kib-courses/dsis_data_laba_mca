# dsis_data_laba_mca

Даннные для [лабораторной работы №2](https://github.com/kib-courses/dsis/tree/master/laba_02) курса по [DSIS](https://github.com/kib-courses/dsis)

Описание смотри здесь: (https://github.com/kib-courses/dsis/tree/master/laba_02)

Данные упакованы и поспличены командой:

```bash
tar -czvf - $(pwd)/cursor_track.csv | split -b 10m - "cursor_track.tar.gz-part-"
```
