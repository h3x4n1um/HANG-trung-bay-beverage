# HANG-trung-bay-beverage

Vietnam beverage classification dataset by manually label image extracted from HANG-trung-bay images set from professor [Nguyen Khang Pham](http://www.cit.ctu.edu.vn/~pnkhang/cv-vi.html)

Note: very few images are mislabeled (it's happen when you are sleepy and you have to create entire dataset to keep up thesis deadline)

## Info

This dataset consists of 2000 images evenly split within 10 types of beverages

| Subset | Ratio | Images per class |
| --- | --- | --- |
| `train` | 60% | 120 |
| `val` | 20% | 40 |
| `test` | 20% | 40 |

## Structure

```
HANG-trung-bay-beverage/
├─ train/
├─ val/
├─ test/
```

```
<train, test or val>/
├─ 7 Up/
├─ Aquafina/
├─ Mirinda cam/
├─ Pepsi/
├─ Revive/
├─ Revive chanh muối/
├─ Sting dâu/
├─ Sting vàng/
├─ Tea Plus/
├─ Tropicana Twister cam/

```

## Benchmark

TODO

## PR

This dataset was used in my graduate thesis (**Using Deep Learning for Merchandise Display Evaluation**), if you're interested, you can find the paper (Vietnamese) [here](https://1drv.ms/b/s!AnAKocoSOJ0VjokxO1xWAE_WDbCUcg?e=YFCpGd)