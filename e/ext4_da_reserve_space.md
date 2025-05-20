# Function: <code>ext4_da_reserve_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8129703e)
Location: fs/ext4/inode.c:1320
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c4669)
Location: fs/ext4/inode.c:1477
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812d9d19)
Location: fs/ext4/inode.c:1504
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fdc20)
Location: fs/ext4/inode.c:1557
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81322400)
Location: fs/ext4/inode.c:1567
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813514b2)
Location: fs/ext4/inode.c:1570
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136a050)
Location: fs/ext4/inode.c:1570
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff8136a050-ffffffff8136a16b: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813934c0)
Location: fs/ext4/inode.c:1586
Inline: False
```
**Symbols:**

```
ffffffff813934c0-ffffffff813935d9: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813abe70)
Location: fs/ext4/inode.c:1605
Inline: False
```
**Symbols:**

```
ffffffff813abe70-ffffffff813abf89: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f81c0)
Location: fs/ext4/inode.c:1454
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_insert_delayed_block
```
**Symbols:**

```
ffffffff813f81c0-ffffffff813f82d9: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81409e60)
Location: fs/ext4/inode.c:1471
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_insert_delayed_block
```
**Symbols:**

```
ffffffff81409e60-ffffffff81409f6a: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81410030)
Location: fs/ext4/inode.c:1470
Inline: False
```
**Symbols:**

```
ffffffff81410030-ffffffff8141013a: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1458
Inline: False
```
**Symbols:**

```
ffffffff81463170-ffffffff814632b2: ext4_da_reserve_space (STB_LOCAL)
ffffffff81cca9f0-ffffffff81ccaa62: ext4_da_reserve_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1471
Inline: False
```
**Symbols:**

```
ffffffff814e0db0-ffffffff814e0f1b: ext4_da_reserve_space (STB_LOCAL)
ffffffff81e7d6ec-ffffffff81e7d75e: ext4_da_reserve_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1485
Inline: False
```
**Symbols:**

```
ffffffff8157a370-ffffffff8157a4db: ext4_da_reserve_space (STB_LOCAL)
ffffffff8206dd0b-ffffffff8206dd7d: ext4_da_reserve_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1443
Inline: False
```
**Symbols:**

```
ffffffff815b1f00-ffffffff815b206b: ext4_da_reserve_space (STB_LOCAL)
ffffffff820eda33-ffffffff820edaa5: ext4_da_reserve_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1455
Inline: False
```
**Symbols:**

```
ffffffff815ead30-ffffffff815eae9b: ext4_da_reserve_space (STB_LOCAL)
ffffffff821cab62-ffffffff821cabd4: ext4_da_reserve_space.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff80001047e918)
Location: fs/ext4/inode.c:1605
Inline: True
```
**Symbols:**

```
ffff80001047e918-ffff80001047eab0: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c063e834)
Location: fs/ext4/inode.c:1605
Inline: False
```
**Symbols:**

```
c063e834-c063e9d0: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a0a00)
Location: fs/ext4/inode.c:1605
Inline: False
```
**Symbols:**

```
c0000000005a0a00-c0000000005a0c08: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000309390)
Location: fs/ext4/inode.c:1605
Inline: False
```
**Symbols:**

```
ffffffe000309390-ffffffe000309512: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a4450)
Location: fs/ext4/inode.c:1605
Inline: False
```
**Symbols:**

```
ffffffff813a4450-ffffffff813a4569: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81394ee0)
Location: fs/ext4/inode.c:1605
Inline: False
```
**Symbols:**

```
ffffffff81394ee0-ffffffff81394ff9: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a1cb0)
Location: fs/ext4/inode.c:1605
Inline: False
```
**Symbols:**

```
ffffffff813a1cb0-ffffffff813a1dc9: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_da_reserve_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b3870)
Location: fs/ext4/inode.c:1605
Inline: False
```
**Symbols:**

```
ffffffff813b3870-ffffffff813b399a: ext4_da_reserve_space (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
