# Function: <code>md_allow_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81697240)
Location: drivers/md/md.c:7718
Inline: True
```
**Symbols:**

```
ffffffff81697240-ffffffff81697312: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f8200)
Location: drivers/md/md.c:7754
Inline: True
```
**Symbols:**

```
ffffffff816f8200-ffffffff816f82d2: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81729a70)
Location: drivers/md/md.c:7811
Inline: True
```
**Symbols:**

```
ffffffff81729a70-ffffffff81729b42: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81742230)
Location: drivers/md/md.c:8063
Inline: True
```
**Symbols:**

```
ffffffff81742230-ffffffff81742386: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b4360)
Location: drivers/md/md.c:8121
Inline: True
```
**Symbols:**

```
ffffffff817b4360-ffffffff817b449c: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817fb690)
Location: drivers/md/md.c:8193
Inline: True
```
**Symbols:**

```
ffffffff817fb690-ffffffff817fb7c6: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81827780)
Location: drivers/md/md.c:8196
Inline: True
```
**Symbols:**

```
ffffffff81827780-ffffffff818278b6: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81869c30)
Location: drivers/md/md.c:8266
Inline: True
```
**Symbols:**

```
ffffffff81869c30-ffffffff81869d66: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8189b9e0)
Location: drivers/md/md.c:8370
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff8189b9e0-ffffffff8189bb16: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff8196a490)
Location: drivers/md/md.c:8567
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff8196a490-ffffffff8196a580: md_allow_write.part.0 (STB_LOCAL)
ffffffff8196a580-ffffffff8196a5e1: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81971010)
Location: drivers/md/md.c:8599
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81971010-ffffffff81971100: md_allow_write.part.0 (STB_LOCAL)
ffffffff81971100-ffffffff81971161: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81955120)
Location: drivers/md/md.c:8577
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81955120-ffffffff8195525b: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819fa750)
Location: drivers/md/md.c:8642
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff819fa750-ffffffff819fa88b: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b61c10)
Location: drivers/md/md.c:8645
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81b61c10-ffffffff81b61d80: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81d0086d)
Location: drivers/md/md.c:8656
Inline: True
Inline callers:
  - drivers/md/md.c:do_md_run
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81cfbdd0-ffffffff81cfbf1f: md_allow_write.part.0 (STB_LOCAL)
ffffffff81cfbf30-ffffffff81cfbf6c: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81d6565d)
Location: drivers/md/md.c:8671
Inline: True
Inline callers:
  - drivers/md/md.c:do_md_run
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81d639f0-ffffffff81d63b3f: md_allow_write.part.0 (STB_LOCAL)
ffffffff81d63b50-ffffffff81d63b8c: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81e1c3dd)
Location: drivers/md/md.c:8746
Inline: True
Inline callers:
  - drivers/md/md.c:do_md_run
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81e1a940-ffffffff81e1aa8f: md_allow_write.part.0 (STB_LOCAL)
ffffffff81e1aaa0-ffffffff81e1aadc: md_allow_write (STB_GLOBAL)
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
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010aeffb0)
Location: drivers/md/md.c:8370
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffff800010aeffb0-ffff800010af00fc: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bd13d8)
Location: drivers/md/md.c:8370
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
c0bd13d8-c0bd154c: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bdbba0)
Location: drivers/md/md.c:8370
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
c000000000bdbba0-c000000000bdbdf8: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e382c)
Location: drivers/md/md.c:8370
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffe0006e382c-ffffffe0006e3990: md_allow_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81841860)
Location: drivers/md/md.c:8370
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81841860-ffffffff81841996: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81808ec0)
Location: drivers/md/md.c:8370
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81808ec0-ffffffff81808ff6: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81890e90)
Location: drivers/md/md.c:8370
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81890e90-ffffffff81890fc6: md_allow_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void md_allow_write(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818aca80)
Location: drivers/md/md.c:8370
Inline: True
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff818aca80-ffffffff818acbad: md_allow_write (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
