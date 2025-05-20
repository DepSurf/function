# Function: <code>free_anon_bdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120ec00)
Location: fs/super.c:907
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff8120ec00-ffffffff8120ec4b: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81235630)
Location: fs/super.c:921
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81235630-ffffffff8123567b: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812481d0)
Location: fs/super.c:967
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff812481d0-ffffffff8124821b: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812539f0)
Location: fs/super.c:970
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff812539f0-ffffffff81253a3b: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81275a70)
Location: fs/super.c:970
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81275a70-ffffffff81275abb: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129c820)
Location: fs/super.c:1025
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff8129c820-ffffffff8129c86b: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b1d28)
Location: fs/super.c:1018
Inline: True
Inline callers:
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812b1210-ffffffff812b122f: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812ceab8)
Location: fs/super.c:1087
Inline: True
Inline callers:
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812cdbd0-ffffffff812cdbef: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e0538)
Location: fs/super.c:1093
Inline: True
Inline callers:
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812df610-ffffffff812df62f: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8131728a)
Location: fs/super.c:1093
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff813163e0-ffffffff813163ff: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8132279a)
Location: fs/super.c:1040
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81321900-ffffffff8132191f: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8132870a)
Location: fs/super.c:1042
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81327990-ffffffff813279af: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81375cda)
Location: fs/super.c:1042
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff81374f60-ffffffff81374f7f: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f4629)
Location: fs/super.c:1041
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff813f4150-ffffffff813f4177: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147d6e9)
Location: fs/super.c:1084
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff8147d1c0-ffffffff8147d1e7: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b2499)
Location: fs/super.c:1095
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff814b1f90-ffffffff814b1fb7: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e4027)
Location: fs/super.c:1210
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
```
**Symbols:**

```
ffffffff814e3730-ffffffff814e3757: free_anon_bdev (STB_GLOBAL)
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
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff8000103881c4)
Location: fs/super.c:1093
Inline: True
Inline callers:
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffff800010385f68-ffff800010385f9c: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (c056ee24)
Location: fs/super.c:1093
Inline: True
Inline callers:
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
c056eddc-c056ee08: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047c3e8)
Location: fs/super.c:1093
Inline: True
Inline callers:
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
c00000000047c370-c00000000047c3b4: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000259c78)
Location: fs/super.c:1093
Inline: True
Inline callers:
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffe000258b30-ffffffe000258b66: free_anon_bdev (STB_GLOBAL)
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
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d8b18)
Location: fs/super.c:1093
Inline: True
Inline callers:
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812d7bf0-ffffffff812d7c0f: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c9798)
Location: fs/super.c:1093
Inline: True
Inline callers:
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812c8870-ffffffff812c888f: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d6928)
Location: fs/super.c:1093
Inline: True
Inline callers:
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812d5a00-ffffffff812d5a1f: free_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_anon_bdev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e6998)
Location: fs/super.c:1093
Inline: True
Inline callers:
  - fs/super.c:kill_anon_super
```
**Symbols:**

```
ffffffff812e6960-ffffffff812e697f: free_anon_bdev (STB_GLOBAL)
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
