# Function: <code>release_tty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e2fc0)
Location: drivers/tty/tty_io.c:1684
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff814e2fc0-ffffffff814e30ac: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815322d0)
Location: drivers/tty/tty_io.c:1686
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff815322d0-ffffffff81532473: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155ea00)
Location: drivers/tty/tty_io.c:1686
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff8155ea00-ffffffff8155eba7: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81571ff0)
Location: drivers/tty/tty_io.c:1454
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
```
**Symbols:**

```
ffffffff81571ff0-ffffffff8157216d: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d8910)
Location: drivers/tty/tty_io.c:1472
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff815d8910-ffffffff815d8ad2: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81610d70)
Location: drivers/tty/tty_io.c:1490
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81610d70-ffffffff81610f2a: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162de60)
Location: drivers/tty/tty_io.c:1502
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff8162de60-ffffffff8162df83: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1504
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81661a30-ffffffff81661b45: release_tty (STB_LOCAL)
ffffffff81664214-ffffffff8166423a: release_tty.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81684080)
Location: drivers/tty/tty_io.c:1504
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81684080-ffffffff816841b3: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81735400)
Location: drivers/tty/tty_io.c:1508
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81735400-ffffffff817355e7: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817515b0)
Location: drivers/tty/tty_io.c:1591
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff817515b0-ffffffff817517b7: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81735440)
Location: drivers/tty/tty_io.c:1606
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81735440-ffffffff81735647: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b5e00)
Location: drivers/tty/tty_io.c:1599
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff817b5e00-ffffffff817b6007: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f1dd0)
Location: drivers/tty/tty_io.c:1587
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff818f1dd0-ffffffff818f1fef: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a49ce0)
Location: drivers/tty/tty_io.c:1582
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81a49ce0-ffffffff81a49efe: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a93ca0)
Location: drivers/tty/tty_io.c:1591
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81a93ca0-ffffffff81a93ebe: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae6710)
Location: drivers/tty/tty_io.c:1589
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81ae6710-ffffffff81ae6922: release_tty (STB_LOCAL)
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
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084f378)
Location: drivers/tty/tty_io.c:1504
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffff80001084f378-ffff80001084f45c: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095b660)
Location: drivers/tty/tty_io.c:1504
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
c095b660-c095b774: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008edc90)
Location: drivers/tty/tty_io.c:1504
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
c0000000008edc90-c0000000008eddb4: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052d10c)
Location: drivers/tty/tty_io.c:1504
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffe00052d10c-ffffffe00052d20e: release_tty (STB_LOCAL)
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
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81649b00)
Location: drivers/tty/tty_io.c:1504
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81649b00-ffffffff81649c33: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81629f50)
Location: drivers/tty/tty_io.c:1504
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81629f50-ffffffff8162a083: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81677ec0)
Location: drivers/tty/tty_io.c:1504
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81677ec0-ffffffff81677ff3: release_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void release_tty(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81693070)
Location: drivers/tty/tty_io.c:1504
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81693070-ffffffff816931a3: release_tty (STB_LOCAL)
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
