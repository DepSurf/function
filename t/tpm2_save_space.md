# Function: <code>tpm2_save_space</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff815bc6ee)
Location: drivers/char/tpm/tpm2-space.c:446
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81622b8e)
Location: drivers/char/tpm/tpm2-space.c:446
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff8165c978)
Location: drivers/char/tpm/tpm2-space.c:450
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81679ce8)
Location: drivers/char/tpm/tpm2-space.c:447
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816b0408)
Location: drivers/char/tpm/tpm2-space.c:483
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816d3108)
Location: drivers/char/tpm/tpm2-space.c:483
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tpm2_save_space(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81787200)
Location: drivers/char/tpm/tpm2-space.c:488
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff81787200-ffffffff81787311: tpm2_save_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tpm2_save_space(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff8179e310)
Location: drivers/char/tpm/tpm2-space.c:488
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff8179e310-ffffffff8179e421: tpm2_save_space (STB_LOCAL)
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
In drivers/char/tpm/tpm2-space.c (ffffffff81780f15)
Location: drivers/char/tpm/tpm2-space.c:488
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff818074c9)
Location: drivers/char/tpm/tpm2-space.c:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff819470e9)
Location: drivers/char/tpm/tpm2-space.c:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81aaa42e)
Location: drivers/char/tpm/tpm2-space.c:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81af5c4e)
Location: drivers/char/tpm/tpm2-space.c:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81b4923e)
Location: drivers/char/tpm/tpm2-space.c:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffff8000108bdda4)
Location: drivers/char/tpm/tpm2-space.c:483
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (c09b7194)
Location: drivers/char/tpm/tpm2-space.c:483
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (c00000000095fe3c)
Location: drivers/char/tpm/tpm2-space.c:483
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffe0005702bc)
Location: drivers/char/tpm/tpm2-space.c:483
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81698b58)
Location: drivers/char/tpm/tpm2-space.c:483
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81676548)
Location: drivers/char/tpm/tpm2-space.c:483
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816c6dc8)
Location: drivers/char/tpm/tpm2-space.c:483
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816e12b8)
Location: drivers/char/tpm/tpm2-space.c:483
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
</ul>
