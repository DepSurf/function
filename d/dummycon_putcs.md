# Function: <code>dummycon_putcs</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff8154f130)
Location: drivers/video/console/dummycon.c:48
Inline: False
```
**Symbols:**

```
ffffffff8154f130-ffffffff8154f13b: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff81566960)
Location: drivers/video/console/dummycon.c:80
Inline: False
```
**Symbols:**

```
ffffffff81566960-ffffffff8156696b: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff81597190)
Location: drivers/video/console/dummycon.c:87
Inline: False
```
**Symbols:**

```
ffffffff81597190-ffffffff8159719b: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff815b84a0)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
ffffffff815b84a0-ffffffff815b84fd: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff81662330)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
ffffffff81662330-ffffffff8166237e: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff81682fc0)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
ffffffff81682fc0-ffffffff8168300e: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff81665dc0)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
ffffffff81665dc0-ffffffff81665e0e: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/console/dummycon.c (0)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
ffffffff816d8e00-ffffffff816d8e7a: dummycon_putcs (STB_LOCAL)
ffffffff81cebee7-ffffffff81cebf02: dummycon_putcs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/console/dummycon.c (0)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
ffffffff81802aa0-ffffffff81802b2c: dummycon_putcs (STB_LOCAL)
ffffffff81eb332b-ffffffff81eb3346: dummycon_putcs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/console/dummycon.c (0)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
ffffffff81931170-ffffffff819311fc: dummycon_putcs (STB_LOCAL)
ffffffff8209033d-ffffffff82090358: dummycon_putcs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/console/dummycon.c (0)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
ffffffff819755c0-ffffffff8197564c: dummycon_putcs (STB_LOCAL)
ffffffff8211069d-ffffffff821106b8: dummycon_putcs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/console/dummycon.c (0)
Location: drivers/video/console/dummycon.c:61
Inline: False
```
**Symbols:**

```
ffffffff819bf630-ffffffff819bf6bc: dummycon_putcs (STB_LOCAL)
ffffffff821ee49a-ffffffff821ee4b5: dummycon_putcs.cold (STB_LOCAL)
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
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffff800010741330)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
ffff800010741330-ffff8000107413d8: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (c08c5e5c)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
c08c5e5c-c08c5edc: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (c00000000089b1e0)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
c00000000089b1e0-c00000000089b290: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffe0004f053c)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
ffffffe0004f053c-ffffffe0004f05b2: dummycon_putcs (STB_LOCAL)
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
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff815ac670)
Location: drivers/video/console/dummycon.c:87
Inline: False
```
**Symbols:**

```
ffffffff815ac670-ffffffff815ac67b: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff8159b810)
Location: drivers/video/console/dummycon.c:87
Inline: False
```
**Symbols:**

```
ffffffff8159b810-ffffffff8159b81b: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff815acc00)
Location: drivers/video/console/dummycon.c:87
Inline: False
```
**Symbols:**

```
ffffffff815acc00-ffffffff815acc0b: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dummycon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/dummycon.c (ffffffff815c6630)
Location: drivers/video/console/dummycon.c:60
Inline: False
```
**Symbols:**

```
ffffffff815c6630-ffffffff815c668d: dummycon_putcs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
