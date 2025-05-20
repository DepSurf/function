# Function: <code>cap_task_setioprio</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (0)
Location: security/commoncap.c:859
Inline: False
```
**Symbols:**

```
ffffffff8136fdf0-ffffffff8136fe00: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (0)
Location: security/commoncap.c:854
Inline: False
```
**Symbols:**

```
ffffffff81386610-ffffffff81386620: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8139b100)
Location: security/commoncap.c:1082
Inline: True
```
**Symbols:**

```
ffffffff8139b100-ffffffff8139b110: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813c0790)
Location: security/commoncap.c:1119
Inline: True
```
**Symbols:**

```
ffffffff813c0790-ffffffff813c07a0: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813f1710)
Location: security/commoncap.c:1125
Inline: True
```
**Symbols:**

```
ffffffff813f1710-ffffffff813f1720: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8140c9e0)
Location: security/commoncap.c:1120
Inline: True
```
**Symbols:**

```
ffffffff8140c9e0-ffffffff8140c9f0: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81439b60)
Location: security/commoncap.c:1117
Inline: False
```
**Symbols:**

```
ffffffff81439b60-ffffffff81439b70: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814539d0)
Location: security/commoncap.c:1117
Inline: False
```
**Symbols:**

```
ffffffff814539d0-ffffffff814539e0: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814a6010)
Location: security/commoncap.c:1119
Inline: False
```
**Symbols:**

```
ffffffff814a6010-ffffffff814a6072: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814c35c0)
Location: security/commoncap.c:1137
Inline: True
```
**Symbols:**

```
ffffffff814c35c0-ffffffff814c35d0: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814c9a30)
Location: security/commoncap.c:1213
Inline: True
```
**Symbols:**

```
ffffffff814c9a30-ffffffff814c9a40: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81522550)
Location: security/commoncap.c:1213
Inline: True
```
**Symbols:**

```
ffffffff81522550-ffffffff81522560: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff815b6070)
Location: security/commoncap.c:1216
Inline: True
```
**Symbols:**

```
ffffffff815b6070-ffffffff815b6086: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff816611a0)
Location: security/commoncap.c:1216
Inline: True
```
**Symbols:**

```
ffffffff816611a0-ffffffff816611b6: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81699450)
Location: security/commoncap.c:1211
Inline: True
```
**Symbols:**

```
ffffffff81699450-ffffffff81699466: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff816d5b00)
Location: security/commoncap.c:1211
Inline: True
```
**Symbols:**

```
ffffffff816d5b00-ffffffff816d5b16: cap_task_setioprio (STB_GLOBAL)
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
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffff80001053ea58)
Location: security/commoncap.c:1117
Inline: True
```
**Symbols:**

```
ffff80001053ea58-ffff80001053ea84: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c06f4a18)
Location: security/commoncap.c:1117
Inline: True
```
**Symbols:**

```
c06f4a18-c06f4a34: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c00000000068f1a0)
Location: security/commoncap.c:1117
Inline: False
```
**Symbols:**

```
c00000000068f1a0-c00000000068f1b4: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffe00039c10e)
Location: security/commoncap.c:1117
Inline: True
```
**Symbols:**

```
ffffffe00039c10e-ffffffe00039c138: cap_task_setioprio (STB_GLOBAL)
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
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8144bfb0)
Location: security/commoncap.c:1117
Inline: False
```
**Symbols:**

```
ffffffff8144bfb0-ffffffff8144bfc0: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8143ca00)
Location: security/commoncap.c:1117
Inline: False
```
**Symbols:**

```
ffffffff8143ca00-ffffffff8143ca10: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81448050)
Location: security/commoncap.c:1117
Inline: False
```
**Symbols:**

```
ffffffff81448050-ffffffff81448060: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cap_task_setioprio(struct task_struct *p, int ioprio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8145f3c0)
Location: security/commoncap.c:1117
Inline: False
```
**Symbols:**

```
ffffffff8145f3c0-ffffffff8145f3d0: cap_task_setioprio (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
