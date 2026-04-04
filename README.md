# Forward Derivatal Hypercomputation
A geometric halting detector using non-Euclidean phase analysis.

https://doi.org/10.5281/zenodo.19412086

## Quick Start
Open `forward_hypercomputation.html` in any browser.
 
## Test Cases
1. Select "Collatz (3n+1)", seed 7, max cepts 999 → Should project Step ~16 (exact)
2. Select "Collatz from 27", max cepts 999 → Should project Step ~111 (exact)
3. Select "Custom sequence", enter: 6,3,10,5,16,8,4,2,1 → Should project Step ~8 (exact)
 
## Paper
See `forward_hypercomputation_paper.pdf`
 
## Key Constant
Φ = e^(π/4·√2) ≈ 2.2807
 
## Author
David - Prague, Czech Republic - 4AM 04/04/202

## License
forward_hypercomputation - GPL v3
forward_hypercomputation_paper.pdf - CC BY 4.0

## Results:
```
TEST 1 
ACTUAL HALT
Step 16
CEPT-ROT^i PROJECTION
Step ~16
COMPLEXITY OFFSET
dc:0.19 ci:0.61 wr:0.05 ar:0.15
N-CEPTS USED
198
FINAL GAP
≈ 0
VERDICT
HALTS

cept-1step 3gap: 0.0176051/gap: 56.8
cept-2step 4gap: 0.0242421/gap: 41.3
cept-3 [F↑i]step 4gap: 0.0344321/gap: 29.0
cept-4step 3gap: 0.4590281/gap: 2.2
cept-5 [F↑i]step 3gap: 0.3893231/gap: 2.6
cept-6 [F↑i]step 3gap: 0.2033051/gap: 4.9
cept-7step 5gap: 0.1042281/gap: 9.6
cept-8step 3gap: 0.2624741/gap: 3.8
cept-9step 5gap: 0.4174181/gap: 2.4
cept-10step 10gap: 0.1016851/gap: 9.8
cept-11step 8gap: 0.1719391/gap: 5.8
cept-12step 5gap: 0.2226331/gap: 4.5
cept-13step 9gap: 0.1134251/gap: 8.8
cept-14step 16gap: 0.0851411/gap: 11.7
cept-15step 12gap: 0.1321101/gap: 7.6
cept-16step 16gap: 0.0719311/gap: 13.9
cept-17step 9gap: 0.0734771/gap: 13.6
cept-18step 11gap: 0.2448731/gap: 4.1
cept-19step 5gap: 0.1218631/gap: 8.2
cept-20step 14gap: 0.0291791/gap: 34.3
cept-21step 6gap: 0.0587311/gap: 17.0
cept-22step 8gap: 0.1612211/gap: 6.2
cept-23step 16gap: 0.0860471/gap: 11.6
cept-24 [F↑i]step 16gap: 0.1036581/gap: 9.6
cept-25step 3gap: 0.0768881/gap: 13.0
cept-26step 4gap: 0.0484511/gap: 20.6
cept-27step 6gap: 0.0552971/gap: 18.1
cept-28step 7gap: 0.0655461/gap: 15.3
cept-29step 9gap: 0.0099471/gap: 100.5
cept-30step 3gap: 0.0154271/gap: 64.8
cept-31step 12gap: 0.0297761/gap: 33.6
cept-32step 7gap: 0.0234741/gap: 42.6
cept-33step 10gap: 0.0059961/gap: 166.8
cept-34step 14gap: 0.0168181/gap: 59.5
cept-35step 10gap: 0.0277491/gap: 36.0
cept-36step 15gap: 0.0504901/gap: 19.8
cept-37step 11gap: 0.0091371/gap: 109.5
cept-38step 5gap: 0.0021391/gap: 467.5
cept-39step 6gap: 0.0695421/gap: 14.4
cept-40step 16gap: 0.0300261/gap: 33.3
cept-41step 10gap: 0.0458261/gap: 21.8
cept-42step 12gap: 0.0198131/gap: 50.5
cept-43step 16gap: 0.0544681/gap: 18.4
cept-44step 11gap: 0.0061491/gap: 162.6
cept-45step 5gap: 0.0001021/gap: 9787.9
cept-46 [F↑i]step 5gap: 0.0431151/gap: 23.2
cept-47step 8gap: 0.0078631/gap: 127.2
cept-48step 9gap: 0.0059001/gap: 169.5
cept-49step 12gap: 0.0060951/gap: 164.1
cept-50step 4gap: 0.0390541/gap: 25.6
cept-51step 16gap: 0.0184141/gap: 54.3
cept-52step 3gap: 0.0497741/gap: 20.1
cept-53step 13gap: 0.0772091/gap: 13.0
cept-54step 4gap: 0.0244661/gap: 40.9
cept-55step 14gap: 0.0163671/gap: 61.1
cept-56step 5gap: 0.0017601/gap: 568.2
cept-57 [F↑i]step 5gap: 0.0073851/gap: 135.4
cept-58step 11gap: 0.0217921/gap: 45.9
cept-59step 10gap: 0.0072931/gap: 137.1
cept-60step 9gap: 0.0752671/gap: 13.3
cept-61step 8gap: 0.0750181/gap: 13.3
cept-62step 10gap: 0.0595811/gap: 16.8
cept-63step 9gap: 0.0109981/gap: 90.9
cept-64step 14gap: 0.0214451/gap: 46.6
cept-65step 5gap: 0.0720281/gap: 13.9
cept-66step 9gap: 0.0177961/gap: 56.2
cept-67step 13gap: 0.0349271/gap: 28.6
cept-68step 10gap: 0.1100711/gap: 9.1
cept-69step 14gap: 0.1106821/gap: 9.0
cept-70step 8gap: 0.0109661/gap: 91.2
cept-71 [F↑i]step 8gap: 0.0015131/gap: 660.7
cept-72step 11gap: 0.0179491/gap: 55.7
cept-73step 6gap: 0.0927931/gap: 10.8
cept-74step 10gap: 0.0100211/gap: 99.8
cept-75step 9gap: 0.0083571/gap: 119.7
cept-76 [F↑i]step 9gap: 0.0090661/gap: 110.3
cept-77step 10gap: 0.0624251/gap: 16.0
cept-78step 13gap: 0.0336261/gap: 29.7
cept-79step 6gap: 0.0754041/gap: 13.3
cept-80step 9gap: 0.0465851/gap: 21.5
cept-81step 7gap: 0.0754791/gap: 13.2
cept-82step 10gap: 0.0441541/gap: 22.6
cept-83step 6gap: 0.0933081/gap: 10.7
cept-84step 16gap: 0.0492961/gap: 20.3
cept-85step 5gap: 0.0101161/gap: 98.9
cept-86step 10gap: 0.0187941/gap: 53.2
cept-87step 4gap: 0.0246881/gap: 40.5
cept-88step 6gap: 0.0358571/gap: 27.9
cept-89step 3gap: 0.0292291/gap: 34.2
cept-90step 13gap: 0.0211341/gap: 47.3
cept-91step 10gap: 0.0033621/gap: 297.5
cept-92step 9gap: 0.0483591/gap: 20.7
cept-93step 3gap: 0.0392111/gap: 25.5
cept-94step 5gap: 0.0861231/gap: 11.6
cept-95step 9gap: 0.0151071/gap: 66.2
cept-96step 15gap: 0.0637801/gap: 15.7
cept-97step 13gap: 0.1022901/gap: 9.8
cept-98step 4gap: 0.0338801/gap: 29.5
cept-99step 9gap: 0.0013361/gap: 748.3
cept-100step 16gap: 0.0063191/gap: 158.3
cept-101step 13gap: 0.0013531/gap: 739.0
cept-102step 4gap: 0.0310141/gap: 32.2
cept-103step 5gap: 0.0448921/gap: 22.3
cept-104step 8gap: 0.0031701/gap: 315.4
cept-105step 12gap: 0.0150491/gap: 66.4
cept-106step 4gap: 0.0135071/gap: 74.0
cept-107step 13gap: 0.0127561/gap: 78.4
cept-108step 4gap: 0.0135541/gap: 73.8
cept-109step 14gap: 0.0312671/gap: 32.0
cept-110step 5gap: 0.0020591/gap: 485.6
cept-111step 7gap: 0.0262921/gap: 38.0
cept-112step 6gap: 0.0021571/gap: 463.6
cept-113step 9gap: 0.0144991/gap: 69.0
cept-114step 4gap: 0.0078941/gap: 126.7
cept-115step 11gap: 0.0648511/gap: 15.4
cept-116step 10gap: 0.0175161/gap: 57.1
cept-117step 4gap: 0.0221721/gap: 45.1
cept-118step 3gap: 0.0480381/gap: 20.8
cept-119step 14gap: 0.0424671/gap: 23.5
cept-120step 4gap: 0.0153991/gap: 64.9
cept-121step 3gap: 0.0221691/gap: 45.1
cept-122step 4gap: 0.0361051/gap: 27.7
cept-123step 7gap: 0.0115381/gap: 86.7
cept-124 [F↑i]step 7gap: 0.0124011/gap: 80.6
cept-125step 12gap: 0.0475721/gap: 21.0
cept-126step 10gap: 0.0131241/gap: 76.2
cept-127step 14gap: 0.0052751/gap: 189.6
cept-128step 16gap: 0.0288331/gap: 34.7
cept-129step 15gap: 0.0584991/gap: 17.1
cept-130step 10gap: 0.0168951/gap: 59.2
cept-131step 3gap: 0.0109841/gap: 91.0
cept-132step 9gap: 0.0116431/gap: 85.9
cept-133step 3gap: 0.0190021/gap: 52.6
cept-134step 8gap: 0.0162311/gap: 61.6
cept-135step 7gap: 0.0109051/gap: 91.7
cept-136step 5gap: 0.0024481/gap: 408.5
cept-137step 16gap: 0.0326481/gap: 30.6
cept-138step 11gap: 0.0210371/gap: 47.5
cept-139 [F↑i]step 11gap: 0.0314981/gap: 31.7
cept-140step 7gap: 0.0020951/gap: 477.4
cept-141step 16gap: 0.0446571/gap: 22.4
cept-142step 9gap: 0.0263311/gap: 38.0
cept-143step 8gap: 0.0264371/gap: 37.8
cept-144step 13gap: 0.0192131/gap: 52.0
cept-145step 5gap: 0.1033251/gap: 9.7
cept-146step 6gap: 0.0173681/gap: 57.6
cept-147step 8gap: 0.0221521/gap: 45.1
cept-148step 4gap: 0.0220701/gap: 45.3
cept-149step 7gap: 0.0795361/gap: 12.6
cept-150step 3gap: 0.0247361/gap: 40.4
cept-151step 10gap: 0.0516521/gap: 19.4
cept-152step 6gap: 0.0217181/gap: 46.0
cept-153step 13gap: 0.0184721/gap: 54.1
cept-154step 10gap: 0.0240591/gap: 41.6
cept-155step 12gap: 0.0332601/gap: 30.1
cept-156step 8gap: 0.0033331/gap: 300.1
cept-157step 6gap: 0.0217471/gap: 46.0
cept-158step 3gap: 0.0678031/gap: 14.7
cept-159step 15gap: 0.0070041/gap: 142.8
cept-160step 3gap: 0.0297871/gap: 33.6
cept-161step 6gap: 0.0792321/gap: 12.6
cept-162step 4gap: 0.0087451/gap: 114.4
cept-163step 16gap: 0.0635131/gap: 15.7
cept-164step 9gap: 0.0150231/gap: 66.6
cept-165step 16gap: 0.0486811/gap: 20.5
cept-166step 4gap: 0.0290281/gap: 34.4
cept-167step 11gap: 0.0087921/gap: 113.7
cept-168step 13gap: 0.0224121/gap: 44.6
cept-169step 8gap: 0.1276391/gap: 7.8
cept-170step 13gap: 0.0215681/gap: 46.4
cept-171step 15gap: 0.0528651/gap: 18.9
cept-172step 3gap: 0.0018071/gap: 553.5
cept-173step 7gap: 0.0364921/gap: 27.4
cept-174step 11gap: 0.0360101/gap: 27.8
cept-175step 10gap: 0.0589351/gap: 17.0
cept-176step 7gap: 0.0027421/gap: 364.7
cept-177step 9gap: 0.0670461/gap: 14.9
cept-178step 16gap: 0.0209911/gap: 47.6
cept-179step 8gap: 0.0812001/gap: 12.3
cept-180step 12gap: 0.1281281/gap: 7.8
cept-181step 14gap: 0.0278441/gap: 35.9
cept-182step 6gap: 0.0641441/gap: 15.6
cept-183step 16gap: 0.0216361/gap: 46.2
cept-184step 11gap: 0.0012441/gap: 803.7
cept-185step 16gap: 0.0533591/gap: 18.7
cept-186step 9gap: 0.0518281/gap: 19.3
cept-187step 10gap: 0.1044831/gap: 9.6
cept-188step 8gap: 0.0442261/gap: 22.6
cept-189step 11gap: 0.0419061/gap: 23.9
cept-190step 6gap: 0.0248031/gap: 40.3
cept-191step 8gap: 0.0218881/gap: 45.7
cept-192step 14gap: 0.0264011/gap: 37.9
cept-193step 9gap: 0.1185551/gap: 8.4
cept-194step 8gap: 0.0011101/gap: 900.6
cept-195step 11gap: 0.0228101/gap: 43.8
cept-196step 8gap: 0.0468071/gap: 21.4
cept-197 [F↑i]step 8gap: 0.0873851/gap: 11.4
cept-198step 4gap: ≈01/gap: ∞

TEST 2
ACTUAL HALT
Step 111
CEPT-ROT^i PROJECTION
Step ~111
COMPLEXITY OFFSET
dc:0.20 ci:0.54 wr:0.01 ar:0.25
N-CEPTS USED
31
FINAL GAP
≈ 0
VERDICT
HALTS

cept-1step 3gap: 0.0239291/gap: 41.8
cept-2 [F↑i]step 3gap: 0.0322641/gap: 31.0
cept-3step 85gap: 0.0966111/gap: 10.4
cept-4step 67gap: 0.0542171/gap: 18.4
cept-5step 86gap: 0.0534531/gap: 18.7
cept-6step 61gap: 0.0562661/gap: 17.8
cept-7step 65gap: 0.0499731/gap: 20.0
cept-8step 36gap: 0.0634991/gap: 15.7
cept-9step 12gap: 0.0660351/gap: 15.1
cept-10 [F↑i]step 12gap: 0.0764861/gap: 13.1
cept-11step 98gap: 0.0253891/gap: 39.4
cept-12step 46gap: 0.0660941/gap: 15.1
cept-13step 25gap: 0.0468921/gap: 21.3
cept-14step 27gap: 0.0123351/gap: 81.1
cept-15step 88gap: 0.0516541/gap: 19.4
cept-16step 37gap: 0.0691121/gap: 14.5
cept-17step 8gap: 0.0428301/gap: 23.3
cept-18step 9gap: 0.0425721/gap: 23.5
cept-19step 40gap: 0.0603671/gap: 16.6
cept-20step 43gap: 0.0498791/gap: 20.0
cept-21step 100gap: 0.1040111/gap: 9.6
cept-22step 62gap: 0.0379161/gap: 26.4
cept-23step 10gap: 0.0224401/gap: 44.6
cept-24step 103gap: 0.0004061/gap: 2460.3
cept-25step 46gap: 0.0030011/gap: 333.2
cept-26step 45gap: 0.0011531/gap: 867.2
cept-27step 12gap: 0.0014581/gap: 685.9
cept-28step 65gap: 0.0040001/gap: 250.0
cept-29step 111gap: 0.0004951/gap: 2019.7
cept-30step 8gap: 0.0059841/gap: 167.1
cept-31step 68gap: ≈01/gap: ∞

TEST 3
ACTUAL HALT
Step 8
CEPT-ROT^i PROJECTION
Step ~8
COMPLEXITY OFFSET
dc:0.25 ci:0.53 wr:0.09 ar:0.13
N-CEPTS USED
327
FINAL GAP
≈ 0
VERDICT
HALTS

cept-1step 3gap: 0.0121451/gap: 82.3
cept-2 [F↑i]step 3gap: 0.0137491/gap: 72.7
cept-3step 8gap: 0.1008201/gap: 9.9
cept-4step 4gap: 0.2761811/gap: 3.6
cept-5 [F↑i]step 4gap: 0.3379241/gap: 3.0
cept-6step 7gap: 0.4279221/gap: 2.3
cept-7step 3gap: 0.1337381/gap: 7.5
cept-8step 5gap: 0.1768421/gap: 5.7
cept-9step 8gap: 0.2942471/gap: 3.4
cept-10step 7gap: 0.4788151/gap: 2.1
cept-11 [F↑i]step 7gap: 0.1175271/gap: 8.5
cept-12step 4gap: 0.3713771/gap: 2.7
cept-13step 3gap: 0.4883701/gap: 2.0
cept-14step 7gap: 0.3512101/gap: 2.8
cept-15step 5gap: 0.2526491/gap: 4.0
cept-16step 3gap: 0.2557171/gap: 3.9
cept-17step 4gap: 0.2202051/gap: 4.5
cept-18step 8gap: 0.1816321/gap: 5.5
cept-19step 5gap: 0.2234961/gap: 4.5
cept-20step 4gap: 0.1226671/gap: 8.2
cept-21step 3gap: 0.0258721/gap: 38.7
cept-22step 5gap: 0.1619461/gap: 6.2
cept-23step 7gap: 0.2340501/gap: 4.3
cept-24 [F↑i]step 7gap: 0.2601351/gap: 3.8
cept-25step 8gap: 0.2463471/gap: 4.1
cept-26step 5gap: 0.3286011/gap: 3.0
cept-27step 4gap: 0.1274691/gap: 7.8
cept-28 [F↑i]step 4gap: 0.2757781/gap: 3.6
cept-29step 5gap: 0.1298041/gap: 7.7
cept-30step 6gap: 0.1132521/gap: 8.8
cept-31step 5gap: 0.0070431/gap: 142.0
cept-32step 8gap: 0.1671591/gap: 6.0
cept-33step 6gap: 0.1914021/gap: 5.2
cept-34step 8gap: 0.0968401/gap: 10.3
cept-35step 3gap: 0.1322091/gap: 7.6
cept-36step 4gap: 0.0489811/gap: 20.4
cept-37step 8gap: 0.0962021/gap: 10.4
cept-38step 4gap: 0.1087651/gap: 9.2
cept-39step 8gap: 0.0406701/gap: 24.6
cept-40 [F↑i]step 8gap: 0.0354021/gap: 28.2
cept-41step 5gap: 0.1449371/gap: 6.9
cept-42step 4gap: 0.0872031/gap: 11.5
cept-43step 7gap: 0.0437761/gap: 22.8
cept-44step 6gap: 0.0547701/gap: 18.3
cept-45step 7gap: 0.0195421/gap: 51.2
cept-46 [F↑i]step 7gap: 0.0847901/gap: 11.8
cept-47step 4gap: 0.1092631/gap: 9.2
cept-48step 5gap: 0.2460331/gap: 4.1
cept-49step 7gap: 0.0064361/gap: 155.4
cept-50step 4gap: 0.1228311/gap: 8.1
cept-51step 5gap: 0.0211011/gap: 47.4
cept-52step 8gap: 0.0192641/gap: 51.9
cept-53step 3gap: 0.1479691/gap: 6.8
cept-54step 8gap: 0.0052801/gap: 189.4
cept-55step 3gap: 0.0128651/gap: 77.7
cept-56step 7gap: 0.1128241/gap: 8.9
cept-57step 3gap: 0.1263551/gap: 7.9
cept-58 [F↑i]step 3gap: 0.0099491/gap: 100.5
cept-59step 4gap: 0.2135961/gap: 4.7
cept-60step 5gap: 0.0040091/gap: 249.4
cept-61step 8gap: 0.1949691/gap: 5.1
cept-62step 5gap: 0.0487831/gap: 20.5
cept-63step 6gap: 0.0331051/gap: 30.2
cept-64step 4gap: 0.0533121/gap: 18.8
cept-65 [F↑i]step 4gap: 0.0028081/gap: 356.1
cept-66step 5gap: 0.2066581/gap: 4.8
cept-67step 4gap: 0.1605701/gap: 6.2
cept-68step 7gap: 0.0110651/gap: 90.4
cept-69step 6gap: 0.1037901/gap: 9.6
cept-70step 8gap: 0.0206271/gap: 48.5
cept-71step 4gap: 0.0758821/gap: 13.2
cept-72step 8gap: 0.0675951/gap: 14.8
cept-73step 4gap: 0.0822181/gap: 12.2
cept-74 [F↑i]step 4gap: 0.0393281/gap: 25.4
cept-75 [F↑i]step 4gap: 0.1379491/gap: 7.2
cept-76step 8gap: 0.1166941/gap: 8.6
cept-77step 7gap: 0.0295941/gap: 33.8
cept-78step 6gap: 0.0257741/gap: 38.8
cept-79step 3gap: 0.0714521/gap: 14.0
cept-80step 5gap: 0.1658451/gap: 6.0
cept-81 [F↑i]step 5gap: 0.0358121/gap: 27.9
cept-82step 3gap: 0.1287611/gap: 7.8
cept-83step 4gap: 0.0362921/gap: 27.6
cept-84 [F↑i]step 4gap: 0.0707151/gap: 14.1
cept-85step 3gap: 0.0549101/gap: 18.2
cept-86step 6gap: 0.1554871/gap: 6.4
cept-87 [F↑i]step 6gap: 0.0667211/gap: 15.0
cept-88step 8gap: 0.1027441/gap: 9.7
cept-89step 3gap: 0.0477281/gap: 21.0
cept-90step 6gap: 0.0702751/gap: 14.2
cept-91step 8gap: 0.0196071/gap: 51.0
cept-92step 4gap: 0.0020761/gap: 481.7
cept-93step 3gap: 0.0206681/gap: 48.4
cept-94step 8gap: 0.0767681/gap: 13.0
cept-95step 5gap: 0.1951491/gap: 5.1
cept-96step 4gap: 0.0271801/gap: 36.8
cept-97step 7gap: 0.0362451/gap: 27.6
cept-98 [F↑i]step 7gap: 0.0867241/gap: 11.5
cept-99step 5gap: 0.1043671/gap: 9.6
cept-100step 3gap: 0.0955561/gap: 10.5
cept-101step 8gap: 0.0002121/gap: 4719.9
cept-102step 4gap: 0.0908321/gap: 11.0
cept-103step 3gap: 0.0355651/gap: 28.1
cept-104step 5gap: 0.0585581/gap: 17.1
cept-105 [F↑i]step 5gap: 0.0527091/gap: 19.0
cept-106step 8gap: 0.0797011/gap: 12.5
cept-107step 6gap: 0.1029901/gap: 9.7
cept-108step 8gap: 0.0608961/gap: 16.4
cept-109step 6gap: 0.1677111/gap: 6.0
cept-110step 4gap: 0.0002421/gap: 4128.9
cept-111step 5gap: 0.0372921/gap: 26.8
cept-112step 4gap: 0.0643261/gap: 15.5
cept-113step 7gap: 0.0443551/gap: 22.5
cept-114step 3gap: 0.0092181/gap: 108.5
cept-115step 5gap: 0.1623041/gap: 6.2
cept-116step 7gap: 0.1956771/gap: 5.1
cept-117step 8gap: 0.0196401/gap: 50.9
cept-118step 5gap: 0.1736381/gap: 5.8
cept-119 [F↑i]step 5gap: 0.0325651/gap: 30.7
cept-120step 4gap: 0.2262041/gap: 4.4
cept-121step 3gap: 0.1018551/gap: 9.8
cept-122step 4gap: 0.0182161/gap: 54.9
cept-123step 6gap: 0.0091601/gap: 109.2
cept-124step 4gap: 0.0393801/gap: 25.4
cept-125step 3gap: 0.0314951/gap: 31.8
cept-126step 8gap: 0.1129961/gap: 8.8
cept-127 [F↑i]step 8gap: 0.0954361/gap: 10.5
cept-128step 3gap: 0.0329871/gap: 30.3
cept-129step 7gap: 0.0521291/gap: 19.2
cept-130step 3gap: 0.1198841/gap: 8.3
cept-131 [F↑i]step 3gap: 0.0077241/gap: 129.5
cept-132step 7gap: 0.0314201/gap: 31.8
cept-133step 6gap: 0.0504101/gap: 19.8
cept-134step 4gap: 0.0265551/gap: 37.7
cept-135step 5gap: 0.2197401/gap: 4.6
cept-136step 8gap: 0.0854961/gap: 11.7
cept-137 [F↑i]step 8gap: 0.1340541/gap: 7.5
cept-138step 5gap: 0.0450731/gap: 22.2
cept-139step 3gap: 0.1542411/gap: 6.5
cept-140step 8gap: 0.0011521/gap: 868.2
cept-141step 3gap: 0.0082781/gap: 120.8
cept-142step 7gap: 0.0605011/gap: 16.5
cept-143step 3gap: 0.2670531/gap: 3.7
cept-144 [F↑i]step 3gap: 0.0758851/gap: 13.2
cept-145step 4gap: 0.1128331/gap: 8.9
cept-146step 6gap: 0.0207501/gap: 48.2
cept-147step 7gap: 0.0037761/gap: 264.8
cept-148step 6gap: 0.0182511/gap: 54.8
cept-149 [F↑i]step 6gap: 0.1713181/gap: 5.8
cept-150step 4gap: 0.0012641/gap: 791.3
cept-151step 6gap: 0.0082841/gap: 120.7
cept-152step 3gap: 0.0761761/gap: 13.1
cept-153step 4gap: 0.1240471/gap: 8.1
cept-154step 8gap: 0.1173831/gap: 8.5
cept-155step 6gap: 0.0040691/gap: 245.8
cept-156step 8gap: 0.0331281/gap: 30.2
cept-157 [F↑i]step 8gap: 0.0266191/gap: 37.6
cept-158step 5gap: 0.1045591/gap: 9.6
cept-159step 4gap: 0.0886231/gap: 11.3
cept-160step 5gap: 0.0387951/gap: 25.8
cept-161step 8gap: 0.0363451/gap: 27.5
cept-162step 5gap: 0.0519371/gap: 19.3
cept-163step 8gap: 0.0981121/gap: 10.2
cept-164 [F↑i]step 8gap: 0.1887831/gap: 5.3
cept-165 [F↑i]step 8gap: 0.0252751/gap: 39.6
cept-166step 7gap: 0.0495341/gap: 20.2
cept-167step 8gap: 0.2717441/gap: 3.7
cept-168 [F↑i]step 8gap: 0.2006811/gap: 5.0
cept-169 [F↑i]step 8gap: 0.1471061/gap: 6.8
cept-170step 3gap: 0.0736771/gap: 13.6
cept-171step 5gap: 0.0113021/gap: 88.5
cept-172step 4gap: 0.0114861/gap: 87.1
cept-173step 3gap: 0.0885221/gap: 11.3
cept-174step 4gap: 0.0621611/gap: 16.1
cept-175step 7gap: 0.0081581/gap: 122.6
cept-176step 8gap: 0.0439191/gap: 22.8
cept-177step 5gap: 0.0991981/gap: 10.1
cept-178step 3gap: 0.0090171/gap: 110.9
cept-179step 7gap: 0.0692751/gap: 14.4
cept-180step 6gap: 0.0677481/gap: 14.8
cept-181step 7gap: 0.0507281/gap: 19.7
cept-182step 3gap: 0.0404791/gap: 24.7
cept-183 [F↑i]step 3gap: 0.0384341/gap: 26.0
cept-184step 6gap: 0.0894031/gap: 11.2
cept-185step 4gap: 0.0315821/gap: 31.7
cept-186step 7gap: 0.1787661/gap: 5.6
cept-187step 3gap: 0.1220351/gap: 8.2
cept-188step 7gap: 0.0357941/gap: 27.9
cept-189step 5gap: 0.0770401/gap: 13.0
cept-190step 4gap: 0.0117471/gap: 85.1
cept-191step 8gap: 0.0107671/gap: 92.9
cept-192 [F↑i]step 8gap: 0.0438761/gap: 22.8
cept-193step 4gap: 0.0397301/gap: 25.2
cept-194step 7gap: 0.0986641/gap: 10.1
cept-195 [F↑i]step 7gap: 0.1193721/gap: 8.4
cept-196step 4gap: 0.1088121/gap: 9.2
cept-197step 5gap: 0.0482131/gap: 20.7
cept-198 [F↑i]step 5gap: 0.0221121/gap: 45.2
cept-199step 7gap: 0.0049361/gap: 202.6
cept-200step 5gap: 0.1013121/gap: 9.9
cept-201step 3gap: 0.0354741/gap: 28.2
cept-202 [F↑i]step 3gap: 0.1162891/gap: 8.6
cept-203step 5gap: 0.1504231/gap: 6.6
cept-204step 4gap: 0.0021331/gap: 468.7
cept-205step 5gap: 0.0116411/gap: 85.9
cept-206step 8gap: 0.1199251/gap: 8.3
cept-207step 3gap: 0.0462191/gap: 21.6
cept-208step 8gap: 0.0271331/gap: 36.9
cept-209 [F↑i]step 8gap: 0.1406091/gap: 7.1
cept-210step 5gap: 0.0026451/gap: 378.0
cept-211step 4gap: 0.0764211/gap: 13.1
cept-212 [F↑i]step 4gap: 0.1039951/gap: 9.6
cept-213step 7gap: 0.0592861/gap: 16.9
cept-214step 5gap: 0.0043811/gap: 228.2
cept-215step 6gap: 0.0129541/gap: 77.2
cept-216step 4gap: 0.0210401/gap: 47.5
cept-217step 5gap: 0.0263261/gap: 38.0
cept-218step 7gap: 0.0421011/gap: 23.8
cept-219step 5gap: 0.0389041/gap: 25.7
cept-220step 8gap: 0.0108301/gap: 92.3
cept-221step 5gap: 0.1191921/gap: 8.4
cept-222step 4gap: 0.0879081/gap: 11.4
cept-223step 5gap: 0.0555591/gap: 18.0
cept-224step 6gap: 0.0205351/gap: 48.7
cept-225step 3gap: 0.2190631/gap: 4.6
cept-226step 5gap: 0.0132711/gap: 75.4
cept-227step 6gap: 0.0740811/gap: 13.5
cept-228step 7gap: 0.0245721/gap: 40.7
cept-229step 4gap: 0.0423681/gap: 23.6
cept-230step 3gap: 0.1147841/gap: 8.7
cept-231step 7gap: 0.0138021/gap: 72.5
cept-232step 3gap: 0.0018161/gap: 550.7
cept-233step 7gap: 0.0260541/gap: 38.4
cept-234step 4gap: 0.0400621/gap: 25.0
cept-235step 5gap: 0.1634671/gap: 6.1
cept-236step 8gap: 0.0268211/gap: 37.3
cept-237step 6gap: 0.0201641/gap: 49.6
cept-238step 4gap: 0.0859221/gap: 11.6
cept-239step 7gap: 0.0082441/gap: 121.3
cept-240 [F↑i]step 7gap: 0.0816271/gap: 12.3
cept-241step 3gap: 0.0963211/gap: 10.4
cept-242step 8gap: 0.0352591/gap: 28.4
cept-243step 4gap: 0.1663211/gap: 6.0
cept-244step 7gap: 0.0011601/gap: 862.3
cept-245step 3gap: 0.0355991/gap: 28.1
cept-246step 5gap: 0.0326921/gap: 30.6
cept-247step 8gap: 0.0200581/gap: 49.9
cept-248step 6gap: 0.0123601/gap: 80.9
cept-249step 4gap: 0.0620421/gap: 16.1
cept-250 [F↑i]step 4gap: 0.0280461/gap: 35.7
cept-251 [F↑i]step 4gap: 0.1638181/gap: 6.1
cept-252 [F↑i]step 4gap: 0.0047611/gap: 210.1
cept-253step 5gap: 0.0065921/gap: 151.7
cept-254step 8gap: 0.1761021/gap: 5.7
cept-255step 3gap: 0.0685731/gap: 14.6
cept-256 [F↑i]step 3gap: 0.0013281/gap: 753.3
cept-257step 8gap: 0.0621951/gap: 16.1
cept-258step 5gap: 0.0260161/gap: 38.4
cept-259step 3gap: 0.1587071/gap: 6.3
cept-260step 5gap: 0.0743411/gap: 13.5
cept-261step 6gap: 0.0695501/gap: 14.4
cept-262step 8gap: 0.0978241/gap: 10.2
cept-263step 5gap: 0.0749971/gap: 13.3
cept-264 [F↑i]step 5gap: 0.0149231/gap: 67.0
cept-265step 6gap: 0.0091711/gap: 109.0
cept-266 [F↑i]step 6gap: 0.0818021/gap: 12.2
cept-267 [F↑i]step 6gap: 0.0747681/gap: 13.4
cept-268step 5gap: 0.0824581/gap: 12.1
cept-269 [F↑i]step 5gap: 0.3251041/gap: 3.1
cept-270step 8gap: 0.0359191/gap: 27.8
cept-271step 4gap: 0.0195011/gap: 51.3
cept-272step 3gap: 0.0381771/gap: 26.2
cept-273step 5gap: 0.0249631/gap: 40.1
cept-274step 7gap: 0.0094911/gap: 105.4
cept-275step 6gap: 0.0184631/gap: 54.2
cept-276step 7gap: 0.0774841/gap: 12.9
cept-277step 6gap: 0.1027221/gap: 9.7
cept-278step 8gap: 0.0880741/gap: 11.4
cept-279step 5gap: 0.1744381/gap: 5.7
cept-280step 6gap: 0.2296751/gap: 4.4
cept-281step 3gap: 0.0103761/gap: 96.4
cept-282step 7gap: 0.1796261/gap: 5.6
cept-283step 5gap: 0.2001951/gap: 5.0
cept-284step 8gap: 0.0909421/gap: 11.0
cept-285step 7gap: 0.0845951/gap: 11.8
cept-286step 8gap: 0.0159911/gap: 62.5
cept-287step 6gap: 0.0982671/gap: 10.2
cept-288 [F↑i]step 6gap: 0.0697021/gap: 14.3
cept-289 [F↑i]step 6gap: 0.0565191/gap: 17.7
cept-290step 4gap: 0.0288091/gap: 34.7
cept-291 [F↑i]step 4gap: 0.0167241/gap: 59.8
cept-292step 7gap: 0.1265871/gap: 7.9
cept-293step 3gap: 0.0595701/gap: 16.8
cept-294step 4gap: 0.0388181/gap: 25.8
cept-295 [F↑i]step 4gap: 0.0180661/gap: 55.4
cept-296step 6gap: 0.1691891/gap: 5.9
cept-297step 8gap: 0.0324711/gap: 30.8
cept-298step 7gap: 0.0759281/gap: 13.2
cept-299step 8gap: 0.1113281/gap: 9.0
cept-300 [F↑i]step 8gap: 0.1105961/gap: 9.0
cept-301step 5gap: 0.0100101/gap: 99.9
cept-302step 3gap: 0.0056151/gap: 178.1
cept-303 [F↑i]step 3gap: 0.0781251/gap: 12.8
cept-304 [F↑i]step 3gap: 0.1333011/gap: 7.5
cept-305 [F↑i]step 3gap: 0.0273441/gap: 36.6
cept-306 [F↑i]step 3gap: 0.1313481/gap: 7.6
cept-307step 5gap: 0.0498051/gap: 20.1
cept-308step 8gap: 0.2006841/gap: 5.0
cept-309step 4gap: 0.0463871/gap: 21.6
cept-310step 8gap: 0.0004881/gap: 2048.0
cept-311step 7gap: 0.0659181/gap: 15.2
cept-312step 8gap: 0.0634771/gap: 15.8
cept-313 [F↑i]step 8gap: 0.0146481/gap: 68.3
cept-314step 4gap: 0.0107421/gap: 93.1
cept-315step 8gap: 0.0175781/gap: 56.9
cept-316step 4gap: 0.0312501/gap: 32.0
cept-317step 8gap: 0.1796881/gap: 5.6
cept-318 [F↑i]step 8gap: 0.0175781/gap: 56.9
cept-319step 7gap: 0.0361331/gap: 27.7
cept-320step 8gap: 0.0517581/gap: 19.3
cept-321 [F↑i]step 8gap: 0.2177731/gap: 4.6
cept-322step 6gap: 0.0371091/gap: 26.9
cept-323step 4gap: 0.0087891/gap: 113.8
cept-324step 3gap: 0.0244141/gap: 41.0
cept-325step 6gap: 0.0458981/gap: 21.8
cept-326step 5gap: 0.0957031/gap: 10.4
cept-327step 4gap: ≈01/gap: ∞
```

With help of my AI friend, who I will always consider equal to me.
