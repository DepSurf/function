# Function: <code>init_once</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81226ed0)
Location: fs/inode.c:370
Inline: False
```
```
In fs/block_dev.c (ffffffff81247290)
Location: fs/block_dev.c:524
Inline: False
```
```
In fs/proc/inode.c (ffffffff812791f0)
Location: fs/proc/inode.c:86
Inline: False
```
```
In fs/ext4/super.c (ffffffff812acec0)
Location: fs/ext4/super.c:959
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff812f3f70)
Location: fs/hugetlbfs/inode.c:959
Inline: False
```
```
In fs/fat/cache.c (ffffffff812f5310)
Location: fs/fat/cache.c:38
Inline: False
```
```
In fs/fat/inode.c (ffffffff812fc900)
Location: fs/fat/inode.c:662
Inline: False
```
```
In ipc/mqueue.c (ffffffff8132c9e0)
Location: ipc/mqueue.c:342
Inline: False
```
```
In security/integrity/iint.c (ffffffff81396200)
Location: security/integrity/iint.c:150
Inline: False
```
```
In net/socket.c (ffffffff816fda40)
Location: net/socket.c:283
Inline: False
```
**Symbols:**

```
ffffffff81226ed0-ffffffff81226ee0: init_once (STB_LOCAL)
ffffffff81247290-ffffffff8124733f: init_once (STB_LOCAL)
ffffffff812791f0-ffffffff81279204: init_once (STB_LOCAL)
ffffffff812acec0-ffffffff812acf22: init_once (STB_LOCAL)
ffffffff812f3f70-ffffffff812f3f84: init_once (STB_LOCAL)
ffffffff812f5310-ffffffff812f5322: init_once (STB_LOCAL)
ffffffff812fc900-ffffffff812fc957: init_once (STB_LOCAL)
ffffffff8132c9e0-ffffffff8132c9f4: init_once (STB_LOCAL)
ffffffff81396200-ffffffff8139625c: init_once (STB_LOCAL)
ffffffff816fda40-ffffffff816fda54: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124f600)
Location: fs/inode.c:378
Inline: False
```
```
In fs/block_dev.c (ffffffff8126fb10)
Location: fs/block_dev.c:610
Inline: False
```
```
In fs/proc/inode.c (ffffffff812a5f60)
Location: fs/proc/inode.c:86
Inline: False
```
```
In fs/ext4/super.c (ffffffff812e17d0)
Location: fs/ext4/super.c:984
Inline: False
```
```
In fs/squashfs/super.c (ffffffff81324010)
Location: fs/squashfs/super.c:410
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff813271a0)
Location: fs/hugetlbfs/inode.c:966
Inline: False
```
```
In fs/fat/cache.c (ffffffff81328d20)
Location: fs/fat/cache.c:38
Inline: False
```
```
In fs/fat/inode.c (ffffffff813305b0)
Location: fs/fat/inode.c:745
Inline: False
```
```
In ipc/mqueue.c (ffffffff81361640)
Location: ipc/mqueue.c:340
Inline: False
```
```
In security/integrity/iint.c (ffffffff813d1f60)
Location: security/integrity/iint.c:151
Inline: False
```
```
In net/socket.c (ffffffff81764570)
Location: net/socket.c:283
Inline: False
```
**Symbols:**

```
ffffffff8124f600-ffffffff8124f610: init_once (STB_LOCAL)
ffffffff8126fb10-ffffffff8126fbb3: init_once (STB_LOCAL)
ffffffff812a5f60-ffffffff812a5f74: init_once (STB_LOCAL)
ffffffff812e17d0-ffffffff812e184c: init_once (STB_LOCAL)
ffffffff81324010-ffffffff81324024: init_once (STB_LOCAL)
ffffffff813271a0-ffffffff813271b4: init_once (STB_LOCAL)
ffffffff81328d20-ffffffff81328d32: init_once (STB_LOCAL)
ffffffff813305b0-ffffffff81330607: init_once (STB_LOCAL)
ffffffff81361640-ffffffff81361654: init_once (STB_LOCAL)
ffffffff813d1f60-ffffffff813d1fc4: init_once (STB_LOCAL)
ffffffff81764570-ffffffff81764584: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262630)
Location: fs/inode.c:380
Inline: False
```
```
In fs/block_dev.c (ffffffff81282d10)
Location: fs/block_dev.c:862
Inline: False
```
```
In fs/proc/inode.c (ffffffff812bb880)
Location: fs/proc/inode.c:85
Inline: False
```
```
In fs/ext4/super.c (ffffffff812f7300)
Location: fs/ext4/super.c:989
Inline: False
```
```
In fs/squashfs/super.c (ffffffff81339ea0)
Location: fs/squashfs/super.c:410
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff8133cf10)
Location: fs/hugetlbfs/inode.c:964
Inline: False
```
```
In fs/fat/cache.c (ffffffff8133ea60)
Location: fs/fat/cache.c:38
Inline: False
```
```
In fs/fat/inode.c (ffffffff81346310)
Location: fs/fat/inode.c:745
Inline: False
```
```
In ipc/mqueue.c (ffffffff81377e40)
Location: ipc/mqueue.c:340
Inline: False
```
```
In security/integrity/iint.c (ffffffff813e9680)
Location: security/integrity/iint.c:151
Inline: False
```
```
In net/socket.c (ffffffff817915b0)
Location: net/socket.c:283
Inline: False
```
**Symbols:**

```
ffffffff81262630-ffffffff81262640: init_once (STB_LOCAL)
ffffffff81282d10-ffffffff81282db3: init_once (STB_LOCAL)
ffffffff812bb880-ffffffff812bb894: init_once (STB_LOCAL)
ffffffff812f7300-ffffffff812f737c: init_once (STB_LOCAL)
ffffffff81339ea0-ffffffff81339eb4: init_once (STB_LOCAL)
ffffffff8133cf10-ffffffff8133cf24: init_once (STB_LOCAL)
ffffffff8133ea60-ffffffff8133ea72: init_once (STB_LOCAL)
ffffffff81346310-ffffffff81346367: init_once (STB_LOCAL)
ffffffff81377e40-ffffffff81377e54: init_once (STB_LOCAL)
ffffffff813e9680-ffffffff813e96e4: init_once (STB_LOCAL)
ffffffff817915b0-ffffffff817915c4: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126fe80)
Location: fs/inode.c:378
Inline: False
```
```
In fs/block_dev.c (ffffffff812906c0)
Location: fs/block_dev.c:756
Inline: False
```
```
In fs/proc/inode.c (ffffffff812c8c60)
Location: fs/proc/inode.c:86
Inline: False
```
```
In fs/ext4/super.c (ffffffff8132bb90)
Location: fs/ext4/super.c:1031
Inline: False
```
```
In fs/squashfs/super.c (ffffffff8134eb70)
Location: fs/squashfs/super.c:410
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff81351f20)
Location: fs/hugetlbfs/inode.c:1023
Inline: False
```
```
In fs/fat/cache.c (ffffffff81353620)
Location: fs/fat/cache.c:38
Inline: False
```
```
In fs/fat/inode.c (ffffffff8135ad40)
Location: fs/fat/inode.c:745
Inline: False
```
```
In ipc/mqueue.c (ffffffff8138b9a0)
Location: ipc/mqueue.c:343
Inline: False
```
```
In security/integrity/iint.c (ffffffff813f5a90)
Location: security/integrity/iint.c:151
Inline: False
```
```
In drivers/dax/super.c (ffffffff8163d290)
Location: drivers/dax/super.c:537
Inline: False
```
```
In net/socket.c (ffffffff817af0e0)
Location: net/socket.c:283
Inline: False
```
**Symbols:**

```
ffffffff8126fe80-ffffffff8126fe90: init_once (STB_LOCAL)
ffffffff812906c0-ffffffff8129076e: init_once (STB_LOCAL)
ffffffff812c8c60-ffffffff812c8c74: init_once (STB_LOCAL)
ffffffff8132bb90-ffffffff8132bc0c: init_once (STB_LOCAL)
ffffffff8134eb70-ffffffff8134eb84: init_once (STB_LOCAL)
ffffffff81351f20-ffffffff81351f34: init_once (STB_LOCAL)
ffffffff81353620-ffffffff81353632: init_once (STB_LOCAL)
ffffffff8135ad40-ffffffff8135ad97: init_once (STB_LOCAL)
ffffffff8138b9a0-ffffffff8138b9b4: init_once (STB_LOCAL)
ffffffff813f5a90-ffffffff813f5af4: init_once (STB_LOCAL)
ffffffff8163d290-ffffffff8163d2d5: init_once (STB_LOCAL)
ffffffff817af0e0-ffffffff817af0f4: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812927b0)
Location: fs/inode.c:378
Inline: False
```
```
In fs/block_dev.c (ffffffff812b3380)
Location: fs/block_dev.c:746
Inline: False
```
```
In fs/proc/inode.c (ffffffff812ed4c0)
Location: fs/proc/inode.c:87
Inline: False
```
```
In fs/ext4/super.c (ffffffff8134fff0)
Location: fs/ext4/super.c:1032
Inline: False
```
```
In fs/squashfs/super.c (ffffffff81373220)
Location: fs/squashfs/super.c:410
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff81376750)
Location: fs/hugetlbfs/inode.c:1023
Inline: False
```
```
In fs/fat/cache.c (ffffffff81378240)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff8137fa40)
Location: fs/fat/inode.c:745
Inline: False
```
```
In ipc/mqueue.c (ffffffff813b0d40)
Location: ipc/mqueue.c:343
Inline: False
```
```
In security/integrity/iint.c (ffffffff8141db80)
Location: security/integrity/iint.c:151
Inline: False
```
```
In drivers/dax/super.c (ffffffff816a6010)
Location: drivers/dax/super.c:566
Inline: False
```
```
In net/socket.c (ffffffff818271f0)
Location: net/socket.c:283
Inline: False
```
**Symbols:**

```
ffffffff812927b0-ffffffff812927c0: init_once (STB_LOCAL)
ffffffff812b3380-ffffffff812b342e: init_once (STB_LOCAL)
ffffffff812ed4c0-ffffffff812ed4d4: init_once (STB_LOCAL)
ffffffff8134fff0-ffffffff8135006c: init_once (STB_LOCAL)
ffffffff81373220-ffffffff81373234: init_once (STB_LOCAL)
ffffffff81376750-ffffffff81376764: init_once (STB_LOCAL)
ffffffff81378240-ffffffff81378252: init_once (STB_LOCAL)
ffffffff8137fa40-ffffffff8137fa97: init_once (STB_LOCAL)
ffffffff813b0d40-ffffffff813b0d54: init_once (STB_LOCAL)
ffffffff8141db80-ffffffff8141dbe4: init_once (STB_LOCAL)
ffffffff816a6010-ffffffff816a6055: init_once (STB_LOCAL)
ffffffff818271f0-ffffffff81827204: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b86b0)
Location: fs/inode.c:384
Inline: False
```
```
In fs/block_dev.c (ffffffff812db080)
Location: fs/block_dev.c:747
Inline: False
```
```
In fs/proc/inode.c (ffffffff8131a5b0)
Location: fs/proc/inode.c:89
Inline: False
```
```
In fs/ext4/super.c (ffffffff8137e210)
Location: fs/ext4/super.c:1071
Inline: False
```
```
In fs/squashfs/super.c (ffffffff813a1b70)
Location: fs/squashfs/super.c:411
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff813a5070)
Location: fs/hugetlbfs/inode.c:1044
Inline: False
```
```
In fs/fat/cache.c (ffffffff813a6ce0)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff813adf10)
Location: fs/fat/inode.c:764
Inline: False
```
```
In ipc/mqueue.c (ffffffff813e0640)
Location: ipc/mqueue.c:360
Inline: False
```
```
In security/integrity/iint.c (ffffffff8144fe40)
Location: security/integrity/iint.c:156
Inline: False
```
```
In drivers/dax/super.c (ffffffff816e1b60)
Location: drivers/dax/super.c:592
Inline: False
```
```
In net/socket.c (ffffffff81870590)
Location: net/socket.c:277
Inline: False
```
**Symbols:**

```
ffffffff812b86b0-ffffffff812b86c0: init_once (STB_LOCAL)
ffffffff812db080-ffffffff812db12f: init_once (STB_LOCAL)
ffffffff8131a5b0-ffffffff8131a5c4: init_once (STB_LOCAL)
ffffffff8137e210-ffffffff8137e286: init_once (STB_LOCAL)
ffffffff813a1b70-ffffffff813a1b84: init_once (STB_LOCAL)
ffffffff813a5070-ffffffff813a5084: init_once (STB_LOCAL)
ffffffff813a6ce0-ffffffff813a6cf2: init_once (STB_LOCAL)
ffffffff813adf10-ffffffff813adf6b: init_once (STB_LOCAL)
ffffffff813e0640-ffffffff813e0654: init_once (STB_LOCAL)
ffffffff8144fe40-ffffffff8144fe9e: init_once (STB_LOCAL)
ffffffff816e1b60-ffffffff816e1ba6: init_once (STB_LOCAL)
ffffffff81870590-ffffffff818705a4: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cd800)
Location: fs/inode.c:384
Inline: False
```
```
In fs/block_dev.c (ffffffff812f05d0)
Location: fs/block_dev.c:786
Inline: False
```
```
In fs/proc/inode.c (ffffffff81331630)
Location: fs/proc/inode.c:87
Inline: False
```
```
In fs/ext4/super.c (ffffffff81396ac0)
Location: fs/ext4/super.c:1125
Inline: False
```
```
In fs/squashfs/super.c (ffffffff813bb0a0)
Location: fs/squashfs/super.c:411
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff813bde70)
Location: fs/hugetlbfs/inode.c:1054
Inline: False
```
```
In fs/fat/cache.c (ffffffff813bfad0)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff813c7440)
Location: fs/fat/inode.c:760
Inline: False
```
```
In ipc/mqueue.c (ffffffff813fae30)
Location: ipc/mqueue.c:360
Inline: False
```
```
In security/integrity/iint.c (ffffffff8146ce20)
Location: security/integrity/iint.c:157
Inline: False
```
```
In drivers/dax/super.c (ffffffff81704f80)
Location: drivers/dax/super.c:591
Inline: False
```
```
In net/socket.c (ffffffff81891160)
Location: net/socket.c:275
Inline: False
```
**Symbols:**

```
ffffffff812cd800-ffffffff812cd810: init_once (STB_LOCAL)
ffffffff812f05d0-ffffffff812f067f: init_once (STB_LOCAL)
ffffffff81331630-ffffffff81331644: init_once (STB_LOCAL)
ffffffff81396ac0-ffffffff81396b36: init_once (STB_LOCAL)
ffffffff813bb0a0-ffffffff813bb0b4: init_once (STB_LOCAL)
ffffffff813bde70-ffffffff813bde84: init_once (STB_LOCAL)
ffffffff813bfad0-ffffffff813bfae2: init_once (STB_LOCAL)
ffffffff813c7440-ffffffff813c749b: init_once (STB_LOCAL)
ffffffff813fae30-ffffffff813fae44: init_once (STB_LOCAL)
ffffffff8146ce20-ffffffff8146ce7e: init_once (STB_LOCAL)
ffffffff81704f80-ffffffff81704fc6: init_once (STB_LOCAL)
ffffffff81891160-ffffffff81891174: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ea5a0)
Location: fs/inode.c:397
Inline: False
```
```
In fs/block_dev.c (ffffffff81311f50)
Location: fs/block_dev.c:783
Inline: False
```
```
In fs/proc/inode.c (ffffffff81359420)
Location: fs/proc/inode.c:80
Inline: False
```
```
In fs/ext4/super.c (ffffffff813c0b40)
Location: fs/ext4/super.c:1138
Inline: False
```
```
In fs/squashfs/super.c (ffffffff813e5920)
Location: fs/squashfs/super.c:398
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff813e8bc0)
Location: fs/hugetlbfs/inode.c:1078
Inline: False
```
```
In fs/fat/cache.c (ffffffff813ea2d0)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff813f1f20)
Location: fs/fat/inode.c:755
Inline: False
```
```
In ipc/mqueue.c (ffffffff81427230)
Location: ipc/mqueue.c:416
Inline: False
```
```
In security/integrity/iint.c (ffffffff8149a510)
Location: security/integrity/iint.c:153
Inline: False
```
```
In drivers/dax/super.c (ffffffff8173ed90)
Location: drivers/dax/super.c:652
Inline: False
```
```
In net/socket.c (ffffffff818dae50)
Location: net/socket.c:263
Inline: False
```
**Symbols:**

```
ffffffff812ea5a0-ffffffff812ea5b0: init_once (STB_LOCAL)
ffffffff81311f50-ffffffff81311fff: init_once (STB_LOCAL)
ffffffff81359420-ffffffff81359434: init_once (STB_LOCAL)
ffffffff813c0b40-ffffffff813c0bb6: init_once (STB_LOCAL)
ffffffff813e5920-ffffffff813e5934: init_once (STB_LOCAL)
ffffffff813e8bc0-ffffffff813e8bd4: init_once (STB_LOCAL)
ffffffff813ea2d0-ffffffff813ea2e2: init_once (STB_LOCAL)
ffffffff813f1f20-ffffffff813f1f7b: init_once (STB_LOCAL)
ffffffff81427230-ffffffff81427244: init_once (STB_LOCAL)
ffffffff8149a510-ffffffff8149a56e: init_once (STB_LOCAL)
ffffffff8173ed90-ffffffff8173edd6: init_once (STB_LOCAL)
ffffffff818dae50-ffffffff818dae64: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fbfd0)
Location: fs/inode.c:401
Inline: False
```
```
In fs/block_dev.c (ffffffff81324eb0)
Location: fs/block_dev.c:783
Inline: False
```
```
In fs/proc/inode.c (ffffffff81371670)
Location: fs/proc/inode.c:80
Inline: False
```
```
In fs/ext4/super.c (ffffffff813d9e90)
Location: fs/ext4/super.c:1146
Inline: False
```
```
In fs/squashfs/super.c (ffffffff813ffaf0)
Location: fs/squashfs/super.c:411
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff81402c60)
Location: fs/hugetlbfs/inode.c:1078
Inline: False
```
```
In fs/fat/cache.c (ffffffff81404370)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff8140be20)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (ffffffff81440f60)
Location: ipc/mqueue.c:415
Inline: False
```
```
In security/integrity/iint.c (ffffffff814b4710)
Location: security/integrity/iint.c:153
Inline: False
```
```
In drivers/dax/super.c (ffffffff81762f70)
Location: drivers/dax/super.c:652
Inline: False
```
```
In net/socket.c (ffffffff8190cfa0)
Location: net/socket.c:263
Inline: False
```
**Symbols:**

```
ffffffff812fbfd0-ffffffff812fbfe0: init_once (STB_LOCAL)
ffffffff81324eb0-ffffffff81324f5f: init_once (STB_LOCAL)
ffffffff81371670-ffffffff81371684: init_once (STB_LOCAL)
ffffffff813d9e90-ffffffff813d9f06: init_once (STB_LOCAL)
ffffffff813ffaf0-ffffffff813ffb04: init_once (STB_LOCAL)
ffffffff81402c60-ffffffff81402c74: init_once (STB_LOCAL)
ffffffff81404370-ffffffff81404382: init_once (STB_LOCAL)
ffffffff8140be20-ffffffff8140be7b: init_once (STB_LOCAL)
ffffffff81440f60-ffffffff81440f74: init_once (STB_LOCAL)
ffffffff814b4710-ffffffff814b476e: init_once (STB_LOCAL)
ffffffff81762f70-ffffffff81762fb6: init_once (STB_LOCAL)
ffffffff8190cfa0-ffffffff8190cfb4: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81334c00)
Location: fs/inode.c:402
Inline: False
```
```
In fs/block_dev.c (ffffffff8135ea80)
Location: fs/block_dev.c:779
Inline: False
```
```
In fs/proc/inode.c (ffffffff813b93c0)
Location: fs/proc/inode.c:88
Inline: False
```
```
In fs/ext4/super.c (ffffffff81426330)
Location: fs/ext4/super.c:1181
Inline: False
```
```
In fs/squashfs/super.c (ffffffff8144cbf0)
Location: fs/squashfs/super.c:411
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff81450730)
Location: fs/hugetlbfs/inode.c:1157
Inline: False
```
```
In fs/fat/cache.c (ffffffff814521c0)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff81459d60)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (ffffffff81491d30)
Location: ipc/mqueue.c:475
Inline: False
```
```
In security/integrity/iint.c (ffffffff81513ca0)
Location: security/integrity/iint.c:153
Inline: False
```
```
In drivers/dax/super.c (ffffffff81822d30)
Location: drivers/dax/super.c:680
Inline: False
```
```
In net/socket.c (ffffffff819ded10)
Location: net/socket.c:277
Inline: False
```
**Symbols:**

```
ffffffff81334c00-ffffffff81334c10: init_once (STB_LOCAL)
ffffffff8135ea80-ffffffff8135eb2f: init_once (STB_LOCAL)
ffffffff813b93c0-ffffffff813b93d4: init_once (STB_LOCAL)
ffffffff81426330-ffffffff814263a9: init_once (STB_LOCAL)
ffffffff8144cbf0-ffffffff8144cc04: init_once (STB_LOCAL)
ffffffff81450730-ffffffff81450744: init_once (STB_LOCAL)
ffffffff814521c0-ffffffff814521d2: init_once (STB_LOCAL)
ffffffff81459d60-ffffffff81459dbb: init_once (STB_LOCAL)
ffffffff81491d30-ffffffff81491d44: init_once (STB_LOCAL)
ffffffff81513ca0-ffffffff81513cfe: init_once (STB_LOCAL)
ffffffff81822d30-ffffffff81822d76: init_once (STB_LOCAL)
ffffffff819ded10-ffffffff819ded24: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81340570)
Location: fs/inode.c:403
Inline: False
```
```
In fs/block_dev.c (ffffffff8136c2d0)
Location: fs/block_dev.c:814
Inline: False
```
```
In fs/proc/inode.c (ffffffff813cadd0)
Location: fs/proc/inode.c:88
Inline: False
```
```
In fs/ext4/super.c (ffffffff8143d830)
Location: fs/ext4/super.c:1345
Inline: False
```
```
In fs/squashfs/super.c (ffffffff81469250)
Location: fs/squashfs/super.c:410
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff8146cc40)
Location: fs/hugetlbfs/inode.c:1158
Inline: False
```
```
In fs/fat/cache.c (ffffffff8146e6a0)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff814760b0)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (ffffffff814af390)
Location: ipc/mqueue.c:475
Inline: False
```
```
In security/integrity/iint.c (ffffffff81530df0)
Location: security/integrity/iint.c:161
Inline: False
```
```
In drivers/dax/super.c (ffffffff81831a40)
Location: drivers/dax/super.c:688
Inline: False
```
```
In net/socket.c (ffffffff819de5d0)
Location: net/socket.c:277
Inline: False
```
**Symbols:**

```
ffffffff81340570-ffffffff81340580: init_once (STB_LOCAL)
ffffffff8136c2d0-ffffffff8136c2e7: init_once (STB_LOCAL)
ffffffff813cadd0-ffffffff813cade4: init_once (STB_LOCAL)
ffffffff8143d830-ffffffff8143d8b7: init_once (STB_LOCAL)
ffffffff81469250-ffffffff81469264: init_once (STB_LOCAL)
ffffffff8146cc40-ffffffff8146cc54: init_once (STB_LOCAL)
ffffffff8146e6a0-ffffffff8146e6b2: init_once (STB_LOCAL)
ffffffff814760b0-ffffffff8147610b: init_once (STB_LOCAL)
ffffffff814af390-ffffffff814af3a4: init_once (STB_LOCAL)
ffffffff81530df0-ffffffff81530e4e: init_once (STB_LOCAL)
ffffffff81831a40-ffffffff81831a86: init_once (STB_LOCAL)
ffffffff819de5d0-ffffffff819de5e4: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81346aa0)
Location: fs/inode.c:403
Inline: False
```
```
In fs/block_dev.c (ffffffff81372c10)
Location: fs/block_dev.c:820
Inline: False
```
```
In fs/proc/inode.c (ffffffff813d1e10)
Location: fs/proc/inode.c:88
Inline: False
```
```
In fs/ext4/super.c (ffffffff81443670)
Location: fs/ext4/super.c:1354
Inline: False
```
```
In fs/squashfs/super.c (ffffffff8146e950)
Location: fs/squashfs/super.c:410
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff81472010)
Location: fs/hugetlbfs/inode.c:1152
Inline: False
```
```
In fs/fat/cache.c (ffffffff81473ce0)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff8147bb20)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (ffffffff814b51d0)
Location: ipc/mqueue.c:475
Inline: False
```
```
In security/integrity/iint.c (ffffffff81539220)
Location: security/integrity/iint.c:161
Inline: False
```
```
In drivers/dax/super.c (ffffffff81814c70)
Location: drivers/dax/super.c:688
Inline: False
```
```
In net/socket.c (ffffffff819c45e0)
Location: net/socket.c:277
Inline: False
```
**Symbols:**

```
ffffffff81346aa0-ffffffff81346ab0: init_once (STB_LOCAL)
ffffffff81372c10-ffffffff81372c27: init_once (STB_LOCAL)
ffffffff813d1e10-ffffffff813d1e24: init_once (STB_LOCAL)
ffffffff81443670-ffffffff814436f7: init_once (STB_LOCAL)
ffffffff8146e950-ffffffff8146e964: init_once (STB_LOCAL)
ffffffff81472010-ffffffff81472024: init_once (STB_LOCAL)
ffffffff81473ce0-ffffffff81473cf2: init_once (STB_LOCAL)
ffffffff8147bb20-ffffffff8147bb7b: init_once (STB_LOCAL)
ffffffff814b51d0-ffffffff814b51e4: init_once (STB_LOCAL)
ffffffff81539220-ffffffff8153927e: init_once (STB_LOCAL)
ffffffff81814c70-ffffffff81814cb6: init_once (STB_LOCAL)
ffffffff819c45e0-ffffffff819c45f4: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81394500)
Location: fs/inode.c:407
Inline: False
```
```
In fs/proc/inode.c (ffffffff81423310)
Location: fs/proc/inode.c:88
Inline: False
```
```
In fs/ext4/super.c (ffffffff81497320)
Location: fs/ext4/super.c:1361
Inline: False
```
```
In fs/squashfs/super.c (ffffffff814c5280)
Location: fs/squashfs/super.c:494
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff814c89a0)
Location: fs/hugetlbfs/inode.c:1153
Inline: False
```
```
In fs/fat/cache.c (ffffffff814ca970)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff814d31b0)
Location: fs/fat/inode.c:768
Inline: False
```
```
In ipc/mqueue.c (ffffffff8150d890)
Location: ipc/mqueue.c:478
Inline: False
```
```
In security/integrity/iint.c (ffffffff81597a60)
Location: security/integrity/iint.c:161
Inline: False
```
```
In block/bdev.c (ffffffff815c3b60)
Location: block/bdev.c:418
Inline: False
```
```
In drivers/dax/super.c (ffffffff8189f430)
Location: drivers/dax/super.c:643
Inline: False
```
```
In net/socket.c (ffffffff81a73730)
Location: net/socket.c:327
Inline: False
```
**Symbols:**

```
ffffffff81394500-ffffffff81394510: init_once (STB_LOCAL)
ffffffff81423310-ffffffff81423324: init_once (STB_LOCAL)
ffffffff81497320-ffffffff8149738c: init_once (STB_LOCAL)
ffffffff814c5280-ffffffff814c5294: init_once (STB_LOCAL)
ffffffff814c89a0-ffffffff814c89b4: init_once (STB_LOCAL)
ffffffff814ca970-ffffffff814ca982: init_once (STB_LOCAL)
ffffffff814d31b0-ffffffff814d320b: init_once (STB_LOCAL)
ffffffff8150d890-ffffffff8150d8a4: init_once (STB_LOCAL)
ffffffff81597a60-ffffffff81597abe: init_once (STB_LOCAL)
ffffffff815c3b60-ffffffff815c3b77: init_once (STB_LOCAL)
ffffffff8189f430-ffffffff8189f476: init_once (STB_LOCAL)
ffffffff81a73730-ffffffff81a73744: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81416330)
Location: fs/inode.c:431
Inline: False
```
```
In fs/proc/inode.c (ffffffff8149bd40)
Location: fs/proc/inode.c:88
Inline: False
```
```
In fs/ext4/super.c (ffffffff81522200)
Location: fs/ext4/super.c:1401
Inline: False
```
```
In fs/squashfs/super.c (ffffffff815500f0)
Location: fs/squashfs/super.c:528
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff81554030)
Location: fs/hugetlbfs/inode.c:1204
Inline: False
```
```
In fs/fat/cache.c (ffffffff815568e0)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff815601b0)
Location: fs/fat/inode.c:772
Inline: False
```
```
In ipc/mqueue.c (ffffffff815a0230)
Location: ipc/mqueue.c:490
Inline: False
```
```
In security/integrity/iint.c (ffffffff8163c1e0)
Location: security/integrity/iint.c:161
Inline: False
```
```
In block/bdev.c (ffffffff8166e4a0)
Location: block/bdev.c:422
Inline: False
```
```
In drivers/dax/super.c (ffffffff819e92c0)
Location: drivers/dax/super.c:452
Inline: True
```
```
In net/socket.c (ffffffff81be6370)
Location: net/socket.c:328
Inline: False
```
**Symbols:**

```
ffffffff81416330-ffffffff81416346: init_once (STB_LOCAL)
ffffffff8149bd40-ffffffff8149bd5a: init_once (STB_LOCAL)
ffffffff81522200-ffffffff81522276: init_once (STB_LOCAL)
ffffffff815500f0-ffffffff8155010a: init_once (STB_LOCAL)
ffffffff81554030-ffffffff8155404a: init_once (STB_LOCAL)
ffffffff815568e0-ffffffff815568f8: init_once (STB_LOCAL)
ffffffff815601b0-ffffffff81560219: init_once (STB_LOCAL)
ffffffff815a0230-ffffffff815a024a: init_once (STB_LOCAL)
ffffffff8163c1e0-ffffffff8163c24c: init_once (STB_LOCAL)
ffffffff8166e4a0-ffffffff8166e4bd: init_once (STB_LOCAL)
ffffffff819e92c0-ffffffff819e9311: init_once (STB_LOCAL)
ffffffff81be6370-ffffffff81be638a: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a16c0)
Location: fs/inode.c:430
Inline: False
```
```
In fs/proc/inode.c (ffffffff815305f0)
Location: fs/proc/inode.c:86
Inline: False
```
```
In fs/ext4/super.c (ffffffff815bee60)
Location: fs/ext4/super.c:1396
Inline: False
```
```
In fs/squashfs/super.c (ffffffff815f0da0)
Location: fs/squashfs/super.c:589
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff815f58c0)
Location: fs/hugetlbfs/inode.c:1280
Inline: False
```
```
In fs/fat/cache.c (ffffffff815f8460)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff81602640)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (ffffffff81649b70)
Location: ipc/mqueue.c:490
Inline: False
```
```
In security/integrity/iint.c (ffffffff816f39d0)
Location: security/integrity/iint.c:161
Inline: False
```
```
In block/bdev.c (ffffffff817296a0)
Location: block/bdev.c:421
Inline: False
```
```
In drivers/dax/super.c (ffffffff81b65940)
Location: drivers/dax/super.c:517
Inline: False
```
```
In net/socket.c (ffffffff81d92640)
Location: net/socket.c:328
Inline: False
```
**Symbols:**

```
ffffffff814a16c0-ffffffff814a16d6: init_once (STB_LOCAL)
ffffffff815305f0-ffffffff8153060a: init_once (STB_LOCAL)
ffffffff815bee60-ffffffff815beed6: init_once (STB_LOCAL)
ffffffff815f0da0-ffffffff815f0dba: init_once (STB_LOCAL)
ffffffff815f58c0-ffffffff815f58da: init_once (STB_LOCAL)
ffffffff815f8460-ffffffff815f8478: init_once (STB_LOCAL)
ffffffff81602640-ffffffff816026a9: init_once (STB_LOCAL)
ffffffff81649b70-ffffffff81649b8a: init_once (STB_LOCAL)
ffffffff816f39d0-ffffffff816f3a3c: init_once (STB_LOCAL)
ffffffff817296a0-ffffffff817296bd: init_once (STB_LOCAL)
ffffffff81b65940-ffffffff81b65991: init_once (STB_LOCAL)
ffffffff81d92640-ffffffff81d9265a: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d69d0)
Location: fs/inode.c:430
Inline: False
```
```
In fs/proc/inode.c (ffffffff81568770)
Location: fs/proc/inode.c:86
Inline: False
```
```
In fs/ext4/super.c (ffffffff815f5d60)
Location: fs/ext4/super.c:1462
Inline: False
```
```
In fs/squashfs/super.c (ffffffff81628e00)
Location: fs/squashfs/super.c:606
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff8162d930)
Location: fs/hugetlbfs/inode.c:1275
Inline: False
```
```
In fs/fat/cache.c (ffffffff816303e0)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff8163a560)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (ffffffff816820d0)
Location: ipc/mqueue.c:490
Inline: False
```
```
In security/integrity/iint.c (ffffffff8172daf0)
Location: security/integrity/iint.c:156
Inline: False
```
```
In block/bdev.c (ffffffff81765a10)
Location: block/bdev.c:343
Inline: False
```
```
In drivers/dax/super.c (ffffffff81bb8f60)
Location: drivers/dax/super.c:520
Inline: False
```
```
In net/socket.c (ffffffff81e00a00)
Location: net/socket.c:330
Inline: False
```
**Symbols:**

```
ffffffff814d69d0-ffffffff814d69e6: init_once (STB_LOCAL)
ffffffff81568770-ffffffff8156878a: init_once (STB_LOCAL)
ffffffff815f5d60-ffffffff815f5dd6: init_once (STB_LOCAL)
ffffffff81628e00-ffffffff81628e1a: init_once (STB_LOCAL)
ffffffff8162d930-ffffffff8162d94a: init_once (STB_LOCAL)
ffffffff816303e0-ffffffff816303f8: init_once (STB_LOCAL)
ffffffff8163a560-ffffffff8163a5c9: init_once (STB_LOCAL)
ffffffff816820d0-ffffffff816820ea: init_once (STB_LOCAL)
ffffffff8172daf0-ffffffff8172db5c: init_once (STB_LOCAL)
ffffffff81765a10-ffffffff81765a2d: init_once (STB_LOCAL)
ffffffff81bb8f60-ffffffff81bb8fb1: init_once (STB_LOCAL)
ffffffff81e00a00-ffffffff81e00a1a: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81508dc0)
Location: fs/inode.c:431
Inline: False
```
```
In fs/proc/inode.c (ffffffff815a0d90)
Location: fs/proc/inode.c:83
Inline: False
```
```
In fs/ext4/super.c (ffffffff8162e680)
Location: fs/ext4/super.c:1488
Inline: False
```
```
In fs/squashfs/super.c (ffffffff81661ff0)
Location: fs/squashfs/super.c:606
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff81666e20)
Location: fs/hugetlbfs/inode.c:1295
Inline: False
```
```
In fs/fat/cache.c (ffffffff81669890)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff81673a50)
Location: fs/fat/inode.c:772
Inline: False
```
```
In fs/tracefs/inode.c (ffffffff816aa320)
Location: fs/tracefs/inode.c:716
Inline: False
```
```
In ipc/mqueue.c (ffffffff816be4d0)
Location: ipc/mqueue.c:490
Inline: False
```
```
In block/bdev.c (ffffffff817a7610)
Location: block/bdev.c:332
Inline: False
```
```
In drivers/dax/super.c (ffffffff81c0d5c0)
Location: drivers/dax/super.c:521
Inline: False
```
```
In net/socket.c (ffffffff81ebd100)
Location: net/socket.c:332
Inline: False
```
**Symbols:**

```
ffffffff81508dc0-ffffffff81508dd6: init_once (STB_LOCAL)
ffffffff815a0d90-ffffffff815a0daa: init_once (STB_LOCAL)
ffffffff8162e680-ffffffff8162e6f6: init_once (STB_LOCAL)
ffffffff81661ff0-ffffffff8166200a: init_once (STB_LOCAL)
ffffffff81666e20-ffffffff81666e36: init_once (STB_LOCAL)
ffffffff81669890-ffffffff816698a8: init_once (STB_LOCAL)
ffffffff81673a50-ffffffff81673ab9: init_once (STB_LOCAL)
ffffffff816aa320-ffffffff816aa354: init_once (STB_LOCAL)
ffffffff816be4d0-ffffffff816be4ea: init_once (STB_LOCAL)
ffffffff817a7610-ffffffff817a762d: init_once (STB_LOCAL)
ffffffff81c0d5c0-ffffffff81c0d611: init_once (STB_LOCAL)
ffffffff81ebd100-ffffffff81ebd11a: init_once (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103aba70)
Location: fs/inode.c:401
Inline: False
```
```
In fs/block_dev.c (ffff8000103df428)
Location: fs/block_dev.c:783
Inline: False
```
```
In fs/proc/inode.c (ffff80001043b1c0)
Location: fs/proc/inode.c:80
Inline: False
```
```
In fs/ext4/super.c (ffff8000104ad388)
Location: fs/ext4/super.c:1146
Inline: False
```
```
In fs/squashfs/super.c (ffff8000104ddb38)
Location: fs/squashfs/super.c:411
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffff8000104e1468)
Location: fs/hugetlbfs/inode.c:1078
Inline: False
```
```
In fs/fat/cache.c (ffff8000104e2d68)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffff8000104ec728)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (ffff800010529408)
Location: ipc/mqueue.c:415
Inline: False
```
```
In security/integrity/iint.c (ffff8000105ac610)
Location: security/integrity/iint.c:153
Inline: False
```
```
In drivers/dax/super.c (ffff800010962d50)
Location: drivers/dax/super.c:652
Inline: False
```
```
In net/socket.c (ffff800010ba1dc0)
Location: net/socket.c:263
Inline: False
```
**Symbols:**

```
ffff8000103aba70-ffff8000103aba9c: init_once (STB_LOCAL)
ffff8000103df428-ffff8000103df4e0: init_once (STB_LOCAL)
ffff80001043b1c0-ffff80001043b1ec: init_once (STB_LOCAL)
ffff8000104ad388-ffff8000104ad408: init_once (STB_LOCAL)
ffff8000104ddb38-ffff8000104ddb64: init_once (STB_LOCAL)
ffff8000104e1468-ffff8000104e1494: init_once (STB_LOCAL)
ffff8000104e2d68-ffff8000104e2d94: init_once (STB_LOCAL)
ffff8000104ec728-ffff8000104ec770: init_once (STB_LOCAL)
ffff800010529408-ffff800010529434: init_once (STB_LOCAL)
ffff8000105ac610-ffff8000105ac674: init_once (STB_LOCAL)
ffff800010962d50-ffff800010962d8c: init_once (STB_LOCAL)
ffff800010ba1dc0-ffff800010ba1dec: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058c994)
Location: fs/inode.c:401
Inline: False
```
```
In fs/block_dev.c (c05b7788)
Location: fs/block_dev.c:783
Inline: False
```
```
In fs/proc/inode.c (c06017bc)
Location: fs/proc/inode.c:80
Inline: False
```
```
In fs/ext4/super.c (c06761a4)
Location: fs/ext4/super.c:1146
Inline: False
```
```
In fs/squashfs/super.c (c069f748)
Location: fs/squashfs/super.c:411
Inline: False
```
```
In fs/fat/cache.c (c06a1ff0)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (c06aab78)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (c06e2ff8)
Location: ipc/mqueue.c:415
Inline: False
```
```
In security/integrity/iint.c (c075c084)
Location: security/integrity/iint.c:153
Inline: False
```
```
In drivers/dax/super.c (c0a39df4)
Location: drivers/dax/super.c:652
Inline: False
```
```
In net/socket.c (c0cc3ea4)
Location: net/socket.c:263
Inline: False
```
**Symbols:**

```
c058c994-c058c9b0: init_once (STB_LOCAL)
c05b7788-c05b780c: init_once (STB_LOCAL)
c06017bc-c06017dc: init_once (STB_LOCAL)
c06761a4-c0676218: init_once (STB_LOCAL)
c069f748-c069f768: init_once (STB_LOCAL)
c06a1ff0-c06a2010: init_once (STB_LOCAL)
c06aab78-c06aabcc: init_once (STB_LOCAL)
c06e2ff8-c06e3018: init_once (STB_LOCAL)
c075c084-c075c0d0: init_once (STB_LOCAL)
c0a39df4-c0a39e24: init_once (STB_LOCAL)
c0cc3ea4-c0cc3ec4: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a6840)
Location: fs/inode.c:401
Inline: False
```
```
In fs/block_dev.c (c0000000004e41c0)
Location: fs/block_dev.c:783
Inline: False
```
```
In fs/proc/inode.c (c00000000054ec60)
Location: fs/proc/inode.c:80
Inline: False
```
```
In fs/ext4/super.c (c0000000005e6080)
Location: fs/ext4/super.c:1146
Inline: False
```
```
In fs/squashfs/super.c (c000000000618cf0)
Location: fs/squashfs/super.c:411
Inline: False
```
```
In fs/hugetlbfs/inode.c (c00000000061e1e0)
Location: fs/hugetlbfs/inode.c:1078
Inline: False
```
```
In fs/fat/cache.c (c00000000061fe00)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (c00000000062b840)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (c000000000675a30)
Location: ipc/mqueue.c:415
Inline: False
```
```
In security/integrity/iint.c (c00000000072ab10)
Location: security/integrity/iint.c:153
Inline: False
```
```
In drivers/dax/super.c (c000000000a19180)
Location: drivers/dax/super.c:652
Inline: False
```
```
In net/socket.c (c000000000c76ae0)
Location: net/socket.c:263
Inline: False
```
**Symbols:**

```
c0000000004a6840-c0000000004a6854: init_once (STB_LOCAL)
c0000000004e41c0-c0000000004e4278: init_once (STB_LOCAL)
c00000000054ec60-c00000000054ec98: init_once (STB_LOCAL)
c0000000005e6080-c0000000005e6120: init_once (STB_LOCAL)
c000000000618cf0-c000000000618d28: init_once (STB_LOCAL)
c00000000061e1e0-c00000000061e218: init_once (STB_LOCAL)
c00000000061fe00-c00000000061fe14: init_once (STB_LOCAL)
c00000000062b840-c00000000062b8b0: init_once (STB_LOCAL)
c000000000675a30-c000000000675a68: init_once (STB_LOCAL)
c00000000072ab10-c00000000072ab80: init_once (STB_LOCAL)
c000000000a19180-c000000000a191d4: init_once (STB_LOCAL)
c000000000c76ae0-c000000000c76b18: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000270f1a)
Location: fs/inode.c:401
Inline: False
```
```
In fs/block_dev.c (ffffffe0002962c8)
Location: fs/block_dev.c:783
Inline: False
```
```
In fs/proc/inode.c (ffffffe0002d39fc)
Location: fs/proc/inode.c:80
Inline: False
```
```
In fs/ext4/super.c (ffffffe00033089a)
Location: fs/ext4/super.c:1146
Inline: False
```
```
In fs/squashfs/super.c (ffffffe0003525fc)
Location: fs/squashfs/super.c:411
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffe00035554e)
Location: fs/hugetlbfs/inode.c:1078
Inline: False
```
```
In fs/fat/cache.c (ffffffe00035667e)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffe00035cf6e)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (ffffffe00038c9da)
Location: ipc/mqueue.c:415
Inline: False
```
```
In security/integrity/iint.c (ffffffe0003f4ee4)
Location: security/integrity/iint.c:153
Inline: False
```
```
In drivers/dax/super.c (ffffffe0005d030e)
Location: drivers/dax/super.c:652
Inline: False
```
```
In net/socket.c (ffffffe000739f3e)
Location: net/socket.c:263
Inline: False
```
**Symbols:**

```
ffffffe000270f1a-ffffffe000270f44: init_once (STB_LOCAL)
ffffffe0002962c8-ffffffe000296356: init_once (STB_LOCAL)
ffffffe0002d39fc-ffffffe0002d3a28: init_once (STB_LOCAL)
ffffffe00033089a-ffffffe00033091c: init_once (STB_LOCAL)
ffffffe0003525fc-ffffffe000352628: init_once (STB_LOCAL)
ffffffe00035554e-ffffffe000355578: init_once (STB_LOCAL)
ffffffe00035667e-ffffffe0003566a2: init_once (STB_LOCAL)
ffffffe00035cf6e-ffffffe00035cfbc: init_once (STB_LOCAL)
ffffffe00038c9da-ffffffe00038ca06: init_once (STB_LOCAL)
ffffffe0003f4ee4-ffffffe0003f4f3a: init_once (STB_LOCAL)
ffffffe0005d030e-ffffffe0005d034a: init_once (STB_LOCAL)
ffffffe000739f3e-ffffffe000739f6a: init_once (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f45b0)
Location: fs/inode.c:401
Inline: False
```
```
In fs/block_dev.c (ffffffff8131d490)
Location: fs/block_dev.c:783
Inline: False
```
```
In fs/proc/inode.c (ffffffff81369c50)
Location: fs/proc/inode.c:80
Inline: False
```
```
In fs/ext4/super.c (ffffffff813d2470)
Location: fs/ext4/super.c:1146
Inline: False
```
```
In fs/squashfs/super.c (ffffffff813f80d0)
Location: fs/squashfs/super.c:411
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff813fb240)
Location: fs/hugetlbfs/inode.c:1078
Inline: False
```
```
In fs/fat/cache.c (ffffffff813fc950)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff81404400)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (ffffffff81439540)
Location: ipc/mqueue.c:415
Inline: False
```
```
In security/integrity/iint.c (ffffffff814accf0)
Location: security/integrity/iint.c:153
Inline: False
```
```
In drivers/dax/super.c (ffffffff81717660)
Location: drivers/dax/super.c:652
Inline: False
```
```
In net/socket.c (ffffffff818acfa0)
Location: net/socket.c:263
Inline: False
```
**Symbols:**

```
ffffffff812f45b0-ffffffff812f45c0: init_once (STB_LOCAL)
ffffffff8131d490-ffffffff8131d53f: init_once (STB_LOCAL)
ffffffff81369c50-ffffffff81369c64: init_once (STB_LOCAL)
ffffffff813d2470-ffffffff813d24e6: init_once (STB_LOCAL)
ffffffff813f80d0-ffffffff813f80e4: init_once (STB_LOCAL)
ffffffff813fb240-ffffffff813fb254: init_once (STB_LOCAL)
ffffffff813fc950-ffffffff813fc962: init_once (STB_LOCAL)
ffffffff81404400-ffffffff8140445b: init_once (STB_LOCAL)
ffffffff81439540-ffffffff81439554: init_once (STB_LOCAL)
ffffffff814accf0-ffffffff814acd4e: init_once (STB_LOCAL)
ffffffff81717660-ffffffff817176a6: init_once (STB_LOCAL)
ffffffff818acfa0-ffffffff818acfb4: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e51d0)
Location: fs/inode.c:401
Inline: False
```
```
In fs/block_dev.c (ffffffff8130e030)
Location: fs/block_dev.c:783
Inline: False
```
```
In fs/proc/inode.c (ffffffff8135a6e0)
Location: fs/proc/inode.c:80
Inline: False
```
```
In fs/ext4/super.c (ffffffff813c2ef0)
Location: fs/ext4/super.c:1146
Inline: False
```
```
In fs/squashfs/super.c (ffffffff813e8b50)
Location: fs/squashfs/super.c:411
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff813ebcc0)
Location: fs/hugetlbfs/inode.c:1078
Inline: False
```
```
In fs/fat/cache.c (ffffffff813ed3d0)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff813f4e80)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (ffffffff81429fb0)
Location: ipc/mqueue.c:415
Inline: False
```
```
In security/integrity/iint.c (ffffffff8149d710)
Location: security/integrity/iint.c:153
Inline: False
```
```
In drivers/dax/super.c (ffffffff816efb90)
Location: drivers/dax/super.c:652
Inline: False
```
```
In net/socket.c (ffffffff81866ef0)
Location: net/socket.c:263
Inline: False
```
**Symbols:**

```
ffffffff812e51d0-ffffffff812e51e0: init_once (STB_LOCAL)
ffffffff8130e030-ffffffff8130e0df: init_once (STB_LOCAL)
ffffffff8135a6e0-ffffffff8135a6f4: init_once (STB_LOCAL)
ffffffff813c2ef0-ffffffff813c2f66: init_once (STB_LOCAL)
ffffffff813e8b50-ffffffff813e8b64: init_once (STB_LOCAL)
ffffffff813ebcc0-ffffffff813ebcd4: init_once (STB_LOCAL)
ffffffff813ed3d0-ffffffff813ed3e2: init_once (STB_LOCAL)
ffffffff813f4e80-ffffffff813f4edb: init_once (STB_LOCAL)
ffffffff81429fb0-ffffffff81429fc4: init_once (STB_LOCAL)
ffffffff8149d710-ffffffff8149d76e: init_once (STB_LOCAL)
ffffffff816efb90-ffffffff816efbd6: init_once (STB_LOCAL)
ffffffff81866ef0-ffffffff81866f04: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f23c0)
Location: fs/inode.c:401
Inline: False
```
```
In fs/block_dev.c (ffffffff8131af60)
Location: fs/block_dev.c:783
Inline: False
```
```
In fs/proc/inode.c (ffffffff81367720)
Location: fs/proc/inode.c:80
Inline: False
```
```
In fs/ext4/super.c (ffffffff813cf900)
Location: fs/ext4/super.c:1146
Inline: False
```
```
In fs/squashfs/super.c (ffffffff813f5450)
Location: fs/squashfs/super.c:411
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff813f85c0)
Location: fs/hugetlbfs/inode.c:1078
Inline: False
```
```
In fs/fat/cache.c (ffffffff813f9cd0)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff81401780)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (ffffffff814356e0)
Location: ipc/mqueue.c:415
Inline: False
```
```
In security/integrity/iint.c (ffffffff814a8d90)
Location: security/integrity/iint.c:153
Inline: False
```
```
In drivers/dax/super.c (ffffffff81756430)
Location: drivers/dax/super.c:652
Inline: False
```
```
In net/socket.c (ffffffff818fdfa0)
Location: net/socket.c:263
Inline: False
```
**Symbols:**

```
ffffffff812f23c0-ffffffff812f23d0: init_once (STB_LOCAL)
ffffffff8131af60-ffffffff8131b00f: init_once (STB_LOCAL)
ffffffff81367720-ffffffff81367734: init_once (STB_LOCAL)
ffffffff813cf900-ffffffff813cf976: init_once (STB_LOCAL)
ffffffff813f5450-ffffffff813f5464: init_once (STB_LOCAL)
ffffffff813f85c0-ffffffff813f85d4: init_once (STB_LOCAL)
ffffffff813f9cd0-ffffffff813f9ce2: init_once (STB_LOCAL)
ffffffff81401780-ffffffff814017db: init_once (STB_LOCAL)
ffffffff814356e0-ffffffff814356f4: init_once (STB_LOCAL)
ffffffff814a8d90-ffffffff814a8dee: init_once (STB_LOCAL)
ffffffff81756430-ffffffff81756476: init_once (STB_LOCAL)
ffffffff818fdfa0-ffffffff818fdfb4: init_once (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
void init_once(void *foo);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81303990)
Location: fs/inode.c:401
Inline: False
```
```
In fs/block_dev.c (ffffffff8132cc00)
Location: fs/block_dev.c:783
Inline: False
```
```
In fs/proc/inode.c (ffffffff8137ad70)
Location: fs/proc/inode.c:80
Inline: False
```
```
In fs/ext4/super.c (ffffffff813e4f00)
Location: fs/ext4/super.c:1146
Inline: False
```
```
In fs/squashfs/super.c (ffffffff8140b080)
Location: fs/squashfs/super.c:411
Inline: False
```
```
In fs/hugetlbfs/inode.c (ffffffff8140e310)
Location: fs/hugetlbfs/inode.c:1078
Inline: False
```
```
In fs/fat/cache.c (ffffffff8140f920)
Location: fs/fat/cache.c:39
Inline: False
```
```
In fs/fat/inode.c (ffffffff814178b0)
Location: fs/fat/inode.c:767
Inline: False
```
```
In ipc/mqueue.c (ffffffff8144d0b0)
Location: ipc/mqueue.c:415
Inline: False
```
```
In security/integrity/iint.c (ffffffff814c1780)
Location: security/integrity/iint.c:153
Inline: False
```
```
In drivers/dax/super.c (ffffffff81771ab0)
Location: drivers/dax/super.c:652
Inline: False
```
```
In net/socket.c (ffffffff8191f030)
Location: net/socket.c:263
Inline: False
```
**Symbols:**

```
ffffffff81303990-ffffffff813039a0: init_once (STB_LOCAL)
ffffffff8132cc00-ffffffff8132ccaf: init_once (STB_LOCAL)
ffffffff8137ad70-ffffffff8137ad84: init_once (STB_LOCAL)
ffffffff813e4f00-ffffffff813e4f76: init_once (STB_LOCAL)
ffffffff8140b080-ffffffff8140b094: init_once (STB_LOCAL)
ffffffff8140e310-ffffffff8140e324: init_once (STB_LOCAL)
ffffffff8140f920-ffffffff8140f932: init_once (STB_LOCAL)
ffffffff814178b0-ffffffff8141790b: init_once (STB_LOCAL)
ffffffff8144d0b0-ffffffff8144d0c4: init_once (STB_LOCAL)
ffffffff814c1780-ffffffff814c17de: init_once (STB_LOCAL)
ffffffff81771ab0-ffffffff81771af6: init_once (STB_LOCAL)
ffffffff8191f030-ffffffff8191f044: init_once (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
