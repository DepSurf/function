# Function: <code>shuffle_show</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff81274480)
Location: mm/shuffle.c:36
Inline: False
```
**Symbols:**

```
ffffffff81274480-ffffffff812744b0: shuffle_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff81283290)
Location: mm/shuffle.c:36
Inline: False
```
**Symbols:**

```
ffffffff81283290-ffffffff812832c0: shuffle_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff812b5330)
Location: mm/shuffle.c:36
Inline: False
```
**Symbols:**

```
ffffffff812b5330-ffffffff812b5360: shuffle_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff812c0430)
Location: mm/shuffle.c:15
Inline: False
```
**Symbols:**

```
ffffffff812c0430-ffffffff812c045b: shuffle_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff812c5bd0)
Location: mm/shuffle.c:15
Inline: False
```
**Symbols:**

```
ffffffff812c5bd0-ffffffff812c5bfb: shuffle_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shuffle.c (0)
Location: mm/shuffle.c:15
Inline: False
```
**Symbols:**

```
ffffffff8130a460-ffffffff8130a4a6: shuffle_show (STB_LOCAL)
ffffffff81cbe574-ffffffff81cbe588: shuffle_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shuffle.c (0)
Location: mm/shuffle.c:15
Inline: False
```
**Symbols:**

```
ffffffff81372f00-ffffffff81372f50: shuffle_show (STB_LOCAL)
ffffffff81e70557-ffffffff81e7056b: shuffle_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffff80001031b1a8)
Location: mm/shuffle.c:36
Inline: False
```
**Symbols:**

```
ffff80001031b1a8-ffff80001031b1f8: shuffle_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (c0535268)
Location: mm/shuffle.c:36
Inline: False
```
**Symbols:**

```
c0535268-c05352a8: shuffle_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (c0000000003eea40)
Location: mm/shuffle.c:36
Inline: False
```
**Symbols:**

```
c0000000003eea40-c0000000003eeac8: shuffle_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffe000220306)
Location: mm/shuffle.c:36
Inline: False
```
**Symbols:**

```
ffffffe000220306-ffffffe00022034e: shuffle_show (STB_LOCAL)
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
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff8127b8e0)
Location: mm/shuffle.c:36
Inline: False
```
**Symbols:**

```
ffffffff8127b8e0-ffffffff8127b910: shuffle_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff8126d7c0)
Location: mm/shuffle.c:36
Inline: False
```
**Symbols:**

```
ffffffff8126d7c0-ffffffff8126d7f0: shuffle_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff81279680)
Location: mm/shuffle.c:36
Inline: False
```
**Symbols:**

```
ffffffff81279680-ffffffff812796b0: shuffle_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shuffle_show(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff81289270)
Location: mm/shuffle.c:36
Inline: False
```
**Symbols:**

```
ffffffff81289270-ffffffff812892a0: shuffle_show (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
