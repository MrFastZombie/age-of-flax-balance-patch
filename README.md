# age-of-flax-balance-patch
Vintage Story patch mod that patches the [Age of Flax](https://mods.vintagestory.at/show/mod/33768) mod to introduce balance changes suggested by a [comment left by Xirsoi](https://mods.vintagestory.at/show/mod/33768#cmt-111003).

### NOTE
Now works with the [fork on the ModDB](https://mods.vintagestory.at/ageofflaxfork)! Make sure you have version 1.1.5 or newer of the fork. The original patches are still included, but may need updates if the original mod updates!

## Installation

Download the zip file from the releases section and put it in `%AppData%/VintagestoryData/Mods`.

WARNING: If you use a launcher, it may store instances elsewhere. The easiest way to get to the folder is to launch the game, open the mods menu, and click "Open mods folder".

## Testing results
Each drop was tested with 5 samples. The averages are not 100% accurate but seem close enough.

For the sake of comparison to vanilla: Simple drops after the patch should be roughly equivalent, except with slightly more seeds.

![Test results of drop rates before patch.](/results-before-patch.png)
![Test results of drop rates after patch.](/results-after-patch.png)

## Summary of Changes

### Ripple drops (before)

| Value  | Primitive | Simple  | Advanced | 
| ------------- | ------------- | ------------- | ------------- |
| flaxGrainDropAvg  | 6 | 8 | 12 |
| flaxGrainDropVar  | 1 | 2 | 2 |
| flaxSeedDropAvg  | 1.2 | 2.1 | 2.5 |

### Ripple drops (after)

| Value  | Primitive | Simple  | Advanced | 
| ------------- | ------------- | ------------- | ------------- |
| flaxGrainDropAvg  | 4.13 | 6 | 7.67 |
| flaxGrainDropVar  | 1 | 1 | 1 |
| flaxSeedDropAvg  | 1.2 | 1.5 | 1.7 |

### Hatchel drops (before)

| Value  | Primitive | Simple  | Advanced | 
| ------------- | ------------- | ------------- | ------------- |
| flaxDropAvg  | 5 | 6 | 8 |
| flaxDropVar  | 2 | 1 | 1 |

### Hatchel drops (after)

| Value  | Primitive | Simple  | Advanced | 
| ------------- | ------------- | ------------- | ------------- |
| flaxDropAvg  | 5.67 | 8.1 | 10.53 |
| flaxDropVar  | 1 | 1 | 1 |

<img width="411" height="450" alt="the-funny" src="https://github.com/user-attachments/assets/d34d3298-0cdf-4ca5-a445-99ed46f33937" />
