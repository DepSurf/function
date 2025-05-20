# Function: <code>tty_reopen</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814df720)
Location: drivers/tty/tty_io.c:1461
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff814df720-ffffffff814df7af: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81531680)
Location: drivers/tty/tty_io.c:1466
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81531680-ffffffff815316ff: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155ddd0)
Location: drivers/tty/tty_io.c:1466
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff8155ddd0-ffffffff8155de4f: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81572d20)
Location: drivers/tty/tty_io.c:1234
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
```
**Symbols:**

```
ffffffff81572d20-ffffffff81572da0: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d70a0)
Location: drivers/tty/tty_io.c:1246
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff815d70a0-ffffffff815d7120: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81610020)
Location: drivers/tty/tty_io.c:1264
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81610020-ffffffff8161009f: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162bba0)
Location: drivers/tty/tty_io.c:1256
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff8162bba0-ffffffff8162bc66: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8165fad0)
Location: drivers/tty/tty_io.c:1258
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff8165fad0-ffffffff8165fb97: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816820f0)
Location: drivers/tty/tty_io.c:1258
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff816820f0-ffffffff816821b7: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81733580)
Location: drivers/tty/tty_io.c:1259
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
```
**Symbols:**

```
ffffffff81733580-ffffffff81733646: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8174f6e0)
Location: drivers/tty/tty_io.c:1339
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
```
**Symbols:**

```
ffffffff8174f6e0-ffffffff8174f7a6: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81733690)
Location: drivers/tty/tty_io.c:1354
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81733690-ffffffff81733756: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b4000)
Location: drivers/tty/tty_io.c:1346
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff817b4000-ffffffff817b40c6: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818efcf0)
Location: drivers/tty/tty_io.c:1338
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff818efcf0-ffffffff818efdc6: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a47dc0)
Location: drivers/tty/tty_io.c:1334
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81a47dc0-ffffffff81a47e96: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a91f60)
Location: drivers/tty/tty_io.c:1343
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81a91f60-ffffffff81a92036: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae4940)
Location: drivers/tty/tty_io.c:1341
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81ae4940-ffffffff81ae4a16: tty_reopen (STB_LOCAL)
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
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084e4c0)
Location: drivers/tty/tty_io.c:1258
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffff80001084e4c0-ffff80001084e5a8: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095a4cc)
Location: drivers/tty/tty_io.c:1258
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
c095a4cc-c095a5c4: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ecb70)
Location: drivers/tty/tty_io.c:1258
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
c0000000008ecb70-c0000000008ecce4: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052cace)
Location: drivers/tty/tty_io.c:1258
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffe00052cace-ffffffe00052cb96: tty_reopen (STB_LOCAL)
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
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81647b70)
Location: drivers/tty/tty_io.c:1258
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81647b70-ffffffff81647c37: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81627fd0)
Location: drivers/tty/tty_io.c:1258
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81627fd0-ffffffff81628097: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81675f30)
Location: drivers/tty/tty_io.c:1258
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81675f30-ffffffff81675ff7: tty_reopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_reopen(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81690650)
Location: drivers/tty/tty_io.c:1258
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81690650-ffffffff81690717: tty_reopen (STB_LOCAL)
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
