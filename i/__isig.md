# Function: <code>__isig</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff814e4460)
Location: drivers/tty/n_tty.c:1107
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff814e4460-ffffffff814e449c: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81535760)
Location: drivers/tty/n_tty.c:1081
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff81535760-ffffffff8153579c: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81561e80)
Location: drivers/tty/n_tty.c:1081
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff81561e80-ffffffff81561ebc: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff815758c0)
Location: drivers/tty/n_tty.c:1081
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff815758c0-ffffffff815758fc: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff815da1e0)
Location: drivers/tty/n_tty.c:1079
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff815da1e0-ffffffff815da21c: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81613480)
Location: drivers/tty/n_tty.c:1097
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff81613480-ffffffff816134bc: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81630530)
Location: drivers/tty/n_tty.c:1110
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff81630530-ffffffff8163056c: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff816644b0)
Location: drivers/tty/n_tty.c:1112
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff816644b0-ffffffff816644ee: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81686b00)
Location: drivers/tty/n_tty.c:1112
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff81686b00-ffffffff81686b3e: __isig (STB_LOCAL)
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
In drivers/tty/n_tty.c (ffffffff81739791)
Location: drivers/tty/n_tty.c:1112
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
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
In drivers/tty/n_tty.c (ffffffff81755c81)
Location: drivers/tty/n_tty.c:1108
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
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
In drivers/tty/n_tty.c (ffffffff817399b8)
Location: drivers/tty/n_tty.c:1109
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
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
In drivers/tty/n_tty.c (ffffffff817ba468)
Location: drivers/tty/n_tty.c:1109
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
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
In drivers/tty/n_tty.c (ffffffff818f69d8)
Location: drivers/tty/n_tty.c:1072
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
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
In drivers/tty/n_tty.c (ffffffff81a4f4f8)
Location: drivers/tty/n_tty.c:1077
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
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
In drivers/tty/n_tty.c (ffffffff81a99708)
Location: drivers/tty/n_tty.c:1076
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
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
In drivers/tty/n_tty.c (ffffffff81aec368)
Location: drivers/tty/n_tty.c:1067
Inline: True
Inline callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
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
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffff8000108543a0)
Location: drivers/tty/n_tty.c:1112
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffff8000108543a0-ffff8000108543ec: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (c095eab8)
Location: drivers/tty/n_tty.c:1112
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
c095eab8-c095eaf8: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (c0000000008f38a0)
Location: drivers/tty/n_tty.c:1112
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
c0000000008f38a0-c0000000008f3910: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffe0005309b4)
Location: drivers/tty/n_tty.c:1112
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffe0005309b4-ffffffe0005309fe: __isig (STB_LOCAL)
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
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8164c580)
Location: drivers/tty/n_tty.c:1112
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff8164c580-ffffffff8164c5be: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8162c9d0)
Location: drivers/tty/n_tty.c:1112
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff8162c9d0-ffffffff8162ca0e: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff8167a940)
Location: drivers/tty/n_tty.c:1112
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff8167a940-ffffffff8167a97e: __isig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __isig(int sig, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_tty.c (ffffffff81694fa0)
Location: drivers/tty/n_tty.c:1112
Inline: False
Direct callers:
  - drivers/tty/n_tty.c:isig
  - drivers/tty/n_tty.c:isig
```
**Symbols:**

```
ffffffff81694fa0-ffffffff81694fde: __isig (STB_LOCAL)
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
