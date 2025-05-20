# Function: <code>tty_flush_works</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e348c)
Location: drivers/tty/tty_io.c:1599
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8153350f)
Location: drivers/tty/tty_io.c:1601
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155fc3f)
Location: drivers/tty/tty_io.c:1601
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81572187)
Location: drivers/tty/tty_io.c:1369
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d6520)
Location: drivers/tty/tty_io.c:1387
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff815d6520-ffffffff815d6573: tty_flush_works (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8160f550)
Location: drivers/tty/tty_io.c:1405
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff8160f550-ffffffff8160f5a3: tty_flush_works (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162c500)
Location: drivers/tty/tty_io.c:1417
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff8162c500-ffffffff8162c553: tty_flush_works (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81660450)
Location: drivers/tty/tty_io.c:1419
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81660450-ffffffff816604a3: tty_flush_works (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81682aa0)
Location: drivers/tty/tty_io.c:1419
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81682aa0-ffffffff81682af3: tty_flush_works (STB_LOCAL)
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
In drivers/tty/tty_io.c (ffffffff817356a8)
Location: drivers/tty/tty_io.c:1423
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
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
In drivers/tty/tty_io.c (ffffffff81751878)
Location: drivers/tty/tty_io.c:1504
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
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
In drivers/tty/tty_io.c (ffffffff81735708)
Location: drivers/tty/tty_io.c:1519
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
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
In drivers/tty/tty_io.c (ffffffff817b60c8)
Location: drivers/tty/tty_io.c:1511
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
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
In drivers/tty/tty_io.c (ffffffff818f20a7)
Location: drivers/tty/tty_io.c:1501
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
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
In drivers/tty/tty_io.c (ffffffff81a49fd7)
Location: drivers/tty/tty_io.c:1497
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
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
In drivers/tty/tty_io.c (ffffffff81a93f97)
Location: drivers/tty/tty_io.c:1506
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
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
In drivers/tty/tty_io.c (ffffffff81ae6a07)
Location: drivers/tty/tty_io.c:1504
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
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
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084ec20)
Location: drivers/tty/tty_io.c:1419
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffff80001084ec20-ffff80001084ec70: tty_flush_works (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095abdc)
Location: drivers/tty/tty_io.c:1419
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
c095abdc-c095ac28: tty_flush_works (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008eddc0)
Location: drivers/tty/tty_io.c:1419
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
c0000000008eddc0-c0000000008ede38: tty_flush_works (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052d20e)
Location: drivers/tty/tty_io.c:1419
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffe00052d20e-ffffffe00052d268: tty_flush_works (STB_LOCAL)
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
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81648520)
Location: drivers/tty/tty_io.c:1419
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81648520-ffffffff81648573: tty_flush_works (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81628980)
Location: drivers/tty/tty_io.c:1419
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81628980-ffffffff816289d3: tty_flush_works (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816768e0)
Location: drivers/tty/tty_io.c:1419
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff816768e0-ffffffff81676933: tty_flush_works (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_flush_works(struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81691000)
Location: drivers/tty/tty_io.c:1419
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release_struct
  - drivers/tty/tty_io.c:tty_kclose
```
**Symbols:**

```
ffffffff81691000-ffffffff81691053: tty_flush_works (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
