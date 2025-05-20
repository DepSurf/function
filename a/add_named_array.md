# Function: <code>add_named_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int add_named_array(const char *val, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81694d50)
Location: drivers/md/md.c:5083
Inline: False
```
**Symbols:**

```
ffffffff81694d50-ffffffff81694e04: add_named_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int add_named_array(const char *val, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f5850)
Location: drivers/md/md.c:5098
Inline: False
```
**Symbols:**

```
ffffffff816f5850-ffffffff816f5904: add_named_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int add_named_array(const char *val, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81726f90)
Location: drivers/md/md.c:5132
Inline: False
```
**Symbols:**

```
ffffffff81726f90-ffffffff81727044: add_named_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int add_named_array(const char *val, struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8173f7b0)
Location: drivers/md/md.c:5332
Inline: False
```
**Symbols:**

```
ffffffff8173f7b0-ffffffff8173f8ff: add_named_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b17d0)
Location: drivers/md/md.c:5377
Inline: False
```
**Symbols:**

```
ffffffff817b17d0-ffffffff817b191f: add_named_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5394
Inline: False
```
**Symbols:**

```
ffffffff817f97f0-ffffffff817f99dc: add_named_array (STB_LOCAL)
ffffffff81800a5e-ffffffff81800a6a: add_named_array.cold.85 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5385
Inline: False
```
**Symbols:**

```
ffffffff818257c0-ffffffff818259ac: add_named_array (STB_LOCAL)
ffffffff8182cc61-ffffffff8182cc6d: add_named_array.cold.84 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5453
Inline: False
```
**Symbols:**

```
ffffffff81867c30-ffffffff81867dcd: add_named_array (STB_LOCAL)
ffffffff8186f1f3-ffffffff8186f1ff: add_named_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5549
Inline: False
```
**Symbols:**

```
ffffffff818999c0-ffffffff81899b5d: add_named_array (STB_LOCAL)
ffffffff818a0fc9-ffffffff818a0fd5: add_named_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5744
Inline: False
```
**Symbols:**

```
ffffffff81968fe0-ffffffff81969173: add_named_array (STB_LOCAL)
ffffffff81970d0b-ffffffff81970d17: add_named_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5779
Inline: False
```
**Symbols:**

```
ffffffff8196faf0-ffffffff8196fc83: add_named_array (STB_LOCAL)
ffffffff81c26df6-ffffffff81c26e02: add_named_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5738
Inline: False
```
**Symbols:**

```
ffffffff81952ea0-ffffffff81953033: add_named_array (STB_LOCAL)
ffffffff81c185e1-ffffffff81c185ed: add_named_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5747
Inline: False
```
**Symbols:**

```
ffffffff819f8420-ffffffff819f85b3: add_named_array (STB_LOCAL)
ffffffff81d27b59-ffffffff81d27b65: add_named_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5736
Inline: False
```
**Symbols:**

```
ffffffff81b5e270-ffffffff81b5e3c7: add_named_array (STB_LOCAL)
ffffffff81ef39a7-ffffffff81ef39bf: add_named_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cfe2d0)
Location: drivers/md/md.c:5722
Inline: False
```
**Symbols:**

```
ffffffff81cfe2d0-ffffffff81cfe477: add_named_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d65440)
Location: drivers/md/md.c:5704
Inline: False
```
**Symbols:**

```
ffffffff81d65440-ffffffff81d655e7: add_named_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1c1c0)
Location: drivers/md/md.c:5850
Inline: False
```
**Symbols:**

```
ffffffff81e1c1c0-ffffffff81e1c36e: add_named_array (STB_LOCAL)
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
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010aeb8e8)
Location: drivers/md/md.c:5549
Inline: False
```
**Symbols:**

```
ffff800010aeb8e8-ffff800010aeba64: add_named_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bcbe50)
Location: drivers/md/md.c:5549
Inline: False
```
**Symbols:**

```
c0bcbe50-c0bcbf94: add_named_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd8e10)
Location: drivers/md/md.c:5549
Inline: False
```
**Symbols:**

```
c000000000bd8e10-c000000000bd8ff8: add_named_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e23b6)
Location: drivers/md/md.c:5549
Inline: False
```
**Symbols:**

```
ffffffe0006e23b6-ffffffe0006e24be: add_named_array (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5549
Inline: False
```
**Symbols:**

```
ffffffff8183f840-ffffffff8183f9dd: add_named_array (STB_LOCAL)
ffffffff81846e49-ffffffff81846e55: add_named_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5549
Inline: False
```
**Symbols:**

```
ffffffff81806ea0-ffffffff8180703d: add_named_array (STB_LOCAL)
ffffffff8180e4a9-ffffffff8180e4b5: add_named_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5549
Inline: False
```
**Symbols:**

```
ffffffff8188ee70-ffffffff8188f00d: add_named_array (STB_LOCAL)
ffffffff81896479-ffffffff81896485: add_named_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int add_named_array(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5549
Inline: False
```
**Symbols:**

```
ffffffff818a9bc0-ffffffff818a9d5d: add_named_array (STB_LOCAL)
ffffffff818b2405-ffffffff818b2411: add_named_array.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kernel_param *kp</code> ➡️ <code>const struct kernel_param *kp</code>
</li>
</ul>
</details>
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
