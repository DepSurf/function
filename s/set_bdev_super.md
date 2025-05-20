# Function: <code>set_bdev_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120e740)
Location: fs/super.c:980
Inline: False
```
**Symbols:**

```
ffffffff8120e740-ffffffff8120e774: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81235170)
Location: fs/super.c:1002
Inline: False
```
**Symbols:**

```
ffffffff81235170-ffffffff812351a4: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81247d10)
Location: fs/super.c:1048
Inline: False
```
**Symbols:**

```
ffffffff81247d10-ffffffff81247d44: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81253540)
Location: fs/super.c:1051
Inline: False
```
**Symbols:**

```
ffffffff81253540-ffffffff8125356b: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81275640)
Location: fs/super.c:1051
Inline: False
```
**Symbols:**

```
ffffffff81275640-ffffffff81275671: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129bf10)
Location: fs/super.c:1106
Inline: False
```
**Symbols:**

```
ffffffff8129bf10-ffffffff8129bf41: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b0fa0)
Location: fs/super.c:1091
Inline: False
```
**Symbols:**

```
ffffffff812b0fa0-ffffffff812b0fd1: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cd940)
Location: fs/super.c:1215
Inline: False
```
**Symbols:**

```
ffffffff812cd940-ffffffff812cd971: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812df36a)
Location: fs/super.c:1253
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffff812dfce0-ffffffff812dfd11: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81316750)
Location: fs/super.c:1253
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffff81316c70-ffffffff81316cec: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81322180)
Location: fs/super.c:1200
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffff81321cd0-ffffffff81321d55: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81328240)
Location: fs/super.c:1202
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffff81327da0-ffffffff81327e25: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81375810)
Location: fs/super.c:1202
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffff81375370-ffffffff813753fc: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f4d40)
Location: fs/super.c:1201
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffff813f4710-ffffffff813f47a2: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147de90)
Location: fs/super.c:1202
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffff8147d800-ffffffff8147d892: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b2c20)
Location: fs/super.c:1229
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffff814b25b0-ffffffff814b263f: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e32f5)
Location: fs/super.c:1309
Inline: True
Inline callers:
  - fs/super.c:super_s_dev_set
```
**Symbols:**

```
ffffffff814e32c0-ffffffff814e32da: set_bdev_super (STB_LOCAL)
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
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010386008)
Location: fs/super.c:1253
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffff800010385fa0-ffff800010385fe8: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (c056eec0)
Location: fs/super.c:1253
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
c056ee6c-c056eea8: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047be3c)
Location: fs/super.c:1253
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
c00000000047bdf0-c00000000047be2c: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe0002588d8)
Location: fs/super.c:1253
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffe000258878-ffffffe0002588ba: set_bdev_super (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d794a)
Location: fs/super.c:1253
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffff812d82c0-ffffffff812d82f1: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c85ca)
Location: fs/super.c:1253
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffff812c8f40-ffffffff812c8f71: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d575a)
Location: fs/super.c:1253
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffff812d60d0-ffffffff812d6101: set_bdev_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int set_bdev_super(struct super_block *s, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e65aa)
Location: fs/super.c:1253
Inline: True
Inline callers:
  - fs/super.c:set_bdev_super_fc
```
**Symbols:**

```
ffffffff812e82e0-ffffffff812e8311: set_bdev_super (STB_LOCAL)
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
