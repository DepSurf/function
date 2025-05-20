# Function: <code>check_tty_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814df7b0)
Location: drivers/tty/tty_io.c:280
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff814df7b0-ffffffff814df859: check_tty_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815307c0)
Location: drivers/tty/tty_io.c:278
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:__tty_hangup
```
**Symbols:**

```
ffffffff815307c0-ffffffff81530893: check_tty_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155cf10)
Location: drivers/tty/tty_io.c:278
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:__tty_hangup
```
**Symbols:**

```
ffffffff8155cf10-ffffffff8155cfe3: check_tty_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81571920)
Location: drivers/tty/tty_io.c:279
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81571920-ffffffff815719f6: check_tty_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d5e80)
Location: drivers/tty/tty_io.c:280
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff815d5e80-ffffffff815d5f6d: check_tty_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:280
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81610a90-ffffffff81610b3f: check_tty_count (STB_LOCAL)
ffffffff8161321a-ffffffff8161325e: check_tty_count.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:281
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff8162d900-ffffffff8162d9af: check_tty_count (STB_LOCAL)
ffffffff816302ce-ffffffff81630312: check_tty_count.cold.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:281
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff816614b0-ffffffff8166155f: check_tty_count (STB_LOCAL)
ffffffff816641d0-ffffffff81664214: check_tty_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:281
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81683b00-ffffffff81683baf: check_tty_count (STB_LOCAL)
ffffffff8168683d-ffffffff81686881: check_tty_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:282
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81735860-ffffffff81735909: check_tty_count.isra.0 (STB_LOCAL)
ffffffff81738653-ffffffff81738697: check_tty_count.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:279
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81751a10-ffffffff81751ab9: check_tty_count.isra.0 (STB_LOCAL)
ffffffff81c073f6-ffffffff81c0743a: check_tty_count.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:280
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81735df0-ffffffff81735e99: check_tty_count.isra.0 (STB_LOCAL)
ffffffff81bf9185-ffffffff81bf91c9: check_tty_count.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:279
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff817b67b0-ffffffff817b6859: check_tty_count.isra.0 (STB_LOCAL)
ffffffff81cf8922-ffffffff81cf8966: check_tty_count.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:278
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff818f0c30-ffffffff818f0cf1: check_tty_count.isra.0 (STB_LOCAL)
ffffffff81ec0835-ffffffff81ec087d: check_tty_count.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a49390)
Location: drivers/tty/tty_io.c:272
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81a49390-ffffffff81a49493: check_tty_count.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a935c0)
Location: drivers/tty/tty_io.c:273
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81a935c0-ffffffff81a936c3: check_tty_count.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae6040)
Location: drivers/tty/tty_io.c:273
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81ae6040-ffffffff81ae6140: check_tty_count (STB_LOCAL)
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
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010850b98)
Location: drivers/tty/tty_io.c:281
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffff800010850b98-ffff800010850ce4: check_tty_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095a3b0)
Location: drivers/tty/tty_io.c:281
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
c095a3b0-c095a4cc: check_tty_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ecd50)
Location: drivers/tty/tty_io.c:281
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
c0000000008ecd50-c0000000008eced4: check_tty_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052e8e6)
Location: drivers/tty/tty_io.c:281
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffe00052e8e6-ffffffe00052e9f4: check_tty_count (STB_LOCAL)
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
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:281
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81649580-ffffffff8164962f: check_tty_count (STB_LOCAL)
ffffffff8164c2bd-ffffffff8164c301: check_tty_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:281
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff816299e0-ffffffff81629a8f: check_tty_count (STB_LOCAL)
ffffffff8162c70d-ffffffff8162c751: check_tty_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:281
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81677940-ffffffff816779ef: check_tty_count (STB_LOCAL)
ffffffff8167a67d-ffffffff8167a6c1: check_tty_count.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int check_tty_count(struct tty_struct *tty, const char *routine);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:281
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81690590-ffffffff81690644: check_tty_count (STB_LOCAL)
ffffffff81694b46-ffffffff81694b8e: check_tty_count.cold (STB_LOCAL)
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
