# Function: <code>get_anon_bdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120eac0)
Location: fs/super.c:875
Inline: False
Direct callers:
  - fs/super.c:ns_set_super
```
**Symbols:**

```
ffffffff8120eac0-ffffffff8120ebbd: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812354f0)
Location: fs/super.c:889
Inline: False
Direct callers:
  - fs/super.c:ns_set_super
```
**Symbols:**

```
ffffffff812354f0-ffffffff812355ed: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81248090)
Location: fs/super.c:935
Inline: False
Direct callers:
  - fs/super.c:ns_set_super
```
**Symbols:**

```
ffffffff81248090-ffffffff8124818d: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812538b0)
Location: fs/super.c:938
Inline: False
Direct callers:
  - fs/super.c:ns_set_super
```
**Symbols:**

```
ffffffff812538b0-ffffffff812539ad: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81275930)
Location: fs/super.c:938
Inline: False
Direct callers:
  - fs/super.c:ns_set_super
```
**Symbols:**

```
ffffffff81275930-ffffffff81275a2d: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129c870)
Location: fs/super.c:993
Inline: False
Direct callers:
  - fs/super.c:ns_set_super
```
**Symbols:**

```
ffffffff8129c870-ffffffff8129c96d: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b1190)
Location: fs/super.c:998
Inline: False
Direct callers:
  - fs/super.c:ns_set_super
```
**Symbols:**

```
ffffffff812b1190-ffffffff812b11d0: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cdb50)
Location: fs/super.c:1067
Inline: False
Direct callers:
  - fs/super.c:set_anon_super_fc
```
**Symbols:**

```
ffffffff812cdb50-ffffffff812cdb90: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812df590)
Location: fs/super.c:1073
Inline: False
Direct callers:
  - fs/super.c:set_anon_super_fc
```
**Symbols:**

```
ffffffff812df590-ffffffff812df5d0: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81316390)
Location: fs/super.c:1073
Inline: True
```
**Symbols:**

```
ffffffff81316390-ffffffff813163d6: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813218b0)
Location: fs/super.c:1020
Inline: True
```
**Symbols:**

```
ffffffff813218b0-ffffffff813218f6: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81327940)
Location: fs/super.c:1022
Inline: True
```
**Symbols:**

```
ffffffff81327940-ffffffff81327986: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81374f10)
Location: fs/super.c:1022
Inline: True
```
**Symbols:**

```
ffffffff81374f10-ffffffff81374f56: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f40f0)
Location: fs/super.c:1021
Inline: True
```
**Symbols:**

```
ffffffff813f40f0-ffffffff813f414e: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147d150)
Location: fs/super.c:1064
Inline: True
```
**Symbols:**

```
ffffffff8147d150-ffffffff8147d1ae: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b1f20)
Location: fs/super.c:1075
Inline: True
```
**Symbols:**

```
ffffffff814b1f20-ffffffff814b1f7e: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e36c0)
Location: fs/super.c:1190
Inline: True
```
**Symbols:**

```
ffffffff814e36c0-ffffffff814e371e: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010385ed8)
Location: fs/super.c:1073
Inline: False
```
**Symbols:**

```
ffff800010385ed8-ffff800010385f38: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c056ed68)
Location: fs/super.c:1073
Inline: False
```
**Symbols:**

```
c056ed68-c056edbc: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047c2a0)
Location: fs/super.c:1073
Inline: False
Direct callers:
  - fs/super.c:set_anon_super_fc
```
**Symbols:**

```
c00000000047c2a0-c00000000047c328: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000258aac)
Location: fs/super.c:1073
Inline: False
```
**Symbols:**

```
ffffffe000258aac-ffffffe000258b04: get_anon_bdev (STB_GLOBAL)
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
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7b70)
Location: fs/super.c:1073
Inline: False
Direct callers:
  - fs/super.c:set_anon_super_fc
```
**Symbols:**

```
ffffffff812d7b70-ffffffff812d7bb0: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c87f0)
Location: fs/super.c:1073
Inline: False
Direct callers:
  - fs/super.c:set_anon_super_fc
```
**Symbols:**

```
ffffffff812c87f0-ffffffff812c8830: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d5980)
Location: fs/super.c:1073
Inline: False
Direct callers:
  - fs/super.c:set_anon_super_fc
```
**Symbols:**

```
ffffffff812d5980-ffffffff812d59c0: get_anon_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_anon_bdev(dev_t *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e68e0)
Location: fs/super.c:1073
Inline: False
Direct callers:
  - fs/super.c:set_anon_super_fc
```
**Symbols:**

```
ffffffff812e68e0-ffffffff812e6920: get_anon_bdev (STB_GLOBAL)
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
