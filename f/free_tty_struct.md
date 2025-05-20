# Function: <code>free_tty_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e0f60)
Location: drivers/tty/tty_io.c:171
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/pty.c:pty_common_install
```
**Symbols:**

```
ffffffff814e0f60-ffffffff814e0f99: free_tty_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81530b70)
Location: drivers/tty/tty_io.c:167
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81530b70-ffffffff81530ba8: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155d2c0)
Location: drivers/tty/tty_io.c:167
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff8155d2c0-ffffffff8155d2f8: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81571fb0)
Location: drivers/tty/tty_io.c:168
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81571fb0-ffffffff81571fe8: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d64e0)
Location: drivers/tty/tty_io.c:169
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff815d64e0-ffffffff815d6518: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8160f510)
Location: drivers/tty/tty_io.c:169
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff8160f510-ffffffff8160f548: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162c4c0)
Location: drivers/tty/tty_io.c:170
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff8162c4c0-ffffffff8162c4f8: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81660410)
Location: drivers/tty/tty_io.c:170
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81660410-ffffffff8166044e: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81682a60)
Location: drivers/tty/tty_io.c:170
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81682a60-ffffffff81682a9e: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817359c8)
Location: drivers/tty/tty_io.c:171
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81751b78)
Location: drivers/tty/tty_io.c:168
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81735f58)
Location: drivers/tty/tty_io.c:169
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b6915)
Location: drivers/tty/tty_io.c:169
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f1983)
Location: drivers/tty/tty_io.c:168
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a49a03)
Location: drivers/tty/tty_io.c:168
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a93c33)
Location: drivers/tty/tty_io.c:169
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae66a3)
Location: drivers/tty/tty_io.c:169
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:release_one_tty
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
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084ebd0)
Location: drivers/tty/tty_io.c:170
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffff80001084ebd0-ffff80001084ec20: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095ab98)
Location: drivers/tty/tty_io.c:170
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
c095ab98-c095abdc: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008edc20)
Location: drivers/tty/tty_io.c:170
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
c0000000008edc20-c0000000008edc90: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052d0b8)
Location: drivers/tty/tty_io.c:170
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffe00052d0b8-ffffffe00052d10c: free_tty_struct (STB_LOCAL)
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
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816484e0)
Location: drivers/tty/tty_io.c:170
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff816484e0-ffffffff8164851e: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81628940)
Location: drivers/tty/tty_io.c:170
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81628940-ffffffff8162897e: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816768a0)
Location: drivers/tty/tty_io.c:170
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff816768a0-ffffffff816768de: free_tty_struct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_tty_struct(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81690fc0)
Location: drivers/tty/tty_io.c:170
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81690fc0-ffffffff81690ffe: free_tty_struct (STB_LOCAL)
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
