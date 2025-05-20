# Function: <code>tty_release_checks</code>

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
In drivers/tty/tty_io.c (ffffffff814e313a)
Location: drivers/tty/tty_io.c:1711
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
In drivers/tty/tty_io.c (ffffffff8153315a)
Location: drivers/tty/tty_io.c:1713
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
In drivers/tty/tty_io.c (ffffffff8155f88a)
Location: drivers/tty/tty_io.c:1713
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
In drivers/tty/tty_io.c (ffffffff8157318d)
Location: drivers/tty/tty_io.c:1481
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d8c0d)
Location: drivers/tty/tty_io.c:1501
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8161134d)
Location: drivers/tty/tty_io.c:1519
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162e0bd)
Location: drivers/tty/tty_io.c:1531
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81661c91)
Location: drivers/tty/tty_io.c:1533
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81684301)
Location: drivers/tty/tty_io.c:1533
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_release_checks(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81733d10)
Location: drivers/tty/tty_io.c:1537
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81733d10-ffffffff81733f08: tty_release_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_release_checks(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8174fe60)
Location: drivers/tty/tty_io.c:1621
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff8174fe60-ffffffff81750058: tty_release_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_release_checks(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81733dd0)
Location: drivers/tty/tty_io.c:1636
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81733dd0-ffffffff81733fc8: tty_release_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tty_release_checks(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b4740)
Location: drivers/tty/tty_io.c:1629
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff817b4740-ffffffff817b492f: tty_release_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_release_checks(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f0510)
Location: drivers/tty/tty_io.c:1617
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff818f0510-ffffffff818f06e4: tty_release_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_release_checks(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a48670)
Location: drivers/tty/tty_io.c:1612
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81a48670-ffffffff81a48847: tty_release_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_release_checks(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a928c0)
Location: drivers/tty/tty_io.c:1621
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81a928c0-ffffffff81a92a9a: tty_release_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_release_checks(struct tty_struct *tty, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae5310)
Location: drivers/tty/tty_io.c:1619
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81ae5310-ffffffff81ae54ea: tty_release_checks (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010851794)
Location: drivers/tty/tty_io.c:1533
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095c2cc)
Location: drivers/tty/tty_io.c:1533
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008eefc4)
Location: drivers/tty/tty_io.c:1533
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052ede4)
Location: drivers/tty/tty_io.c:1533
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81649d81)
Location: drivers/tty/tty_io.c:1533
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162a1d1)
Location: drivers/tty/tty_io.c:1533
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81678141)
Location: drivers/tty/tty_io.c:1533
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816932f1)
Location: drivers/tty/tty_io.c:1533
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_release
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
