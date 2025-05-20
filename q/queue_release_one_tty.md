# Function: <code>queue_release_one_tty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814dfa40)
Location: drivers/tty/tty_io.c:1647
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:proc_clear_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff814dfa40-ffffffff814dfa94: queue_release_one_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81530a00)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:proc_clear_tty
```
**Symbols:**

```
ffffffff81530a00-ffffffff81530a54: queue_release_one_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155d150)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:__tty_hangup
  - drivers/tty/tty_io.c:__proc_set_tty
  - drivers/tty/tty_io.c:proc_clear_tty
```
**Symbols:**

```
ffffffff8155d150-ffffffff8155d1a4: queue_release_one_tty (STB_LOCAL)
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
In drivers/tty/tty_io.c (ffffffff81571e32)
Location: drivers/tty/tty_io.c:1417
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_kref_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d63a0)
Location: drivers/tty/tty_io.c:1435
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff815d63a0-ffffffff815d63f4: queue_release_one_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8160f3d0)
Location: drivers/tty/tty_io.c:1453
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff8160f3d0-ffffffff8160f424: queue_release_one_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162c380)
Location: drivers/tty/tty_io.c:1465
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff8162c380-ffffffff8162c3d4: queue_release_one_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816602d0)
Location: drivers/tty/tty_io.c:1467
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff816602d0-ffffffff81660324: queue_release_one_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81682920)
Location: drivers/tty/tty_io.c:1467
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff81682920-ffffffff81682974: queue_release_one_tty (STB_LOCAL)
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
In drivers/tty/tty_io.c (ffffffff81738262)
Location: drivers/tty/tty_io.c:1471
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
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
In drivers/tty/tty_io.c (ffffffff8175462d)
Location: drivers/tty/tty_io.c:1552
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
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
In drivers/tty/tty_io.c (ffffffff817382ea)
Location: drivers/tty/tty_io.c:1567
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
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
In drivers/tty/tty_io.c (ffffffff817b8d8a)
Location: drivers/tty/tty_io.c:1559
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
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
In drivers/tty/tty_io.c (ffffffff818f4d80)
Location: drivers/tty/tty_io.c:1549
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
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
In drivers/tty/tty_io.c (ffffffff81a4d39f)
Location: drivers/tty/tty_io.c:1544
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
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
In drivers/tty/tty_io.c (ffffffff81a9769d)
Location: drivers/tty/tty_io.c:1553
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
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
In drivers/tty/tty_io.c (ffffffff81aea0db)
Location: drivers/tty/tty_io.c:1551
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
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
In drivers/tty/tty_io.c (ffff80001084f308)
Location: drivers/tty/tty_io.c:1467
Inline: True
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
In drivers/tty/tty_io.c (c095b600)
Location: drivers/tty/tty_io.c:1467
Inline: True
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
In drivers/tty/tty_io.c (c0000000008ed9fc)
Location: drivers/tty/tty_io.c:1467
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_kref_put
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052cecc)
Location: drivers/tty/tty_io.c:1467
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffe00052cecc-ffffffe00052cf24: queue_release_one_tty (STB_LOCAL)
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
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816483a0)
Location: drivers/tty/tty_io.c:1467
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff816483a0-ffffffff816483f4: queue_release_one_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81628800)
Location: drivers/tty/tty_io.c:1467
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff81628800-ffffffff81628854: queue_release_one_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81676760)
Location: drivers/tty/tty_io.c:1467
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff81676760-ffffffff816767b4: queue_release_one_tty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81690e80)
Location: drivers/tty/tty_io.c:1467
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
**Symbols:**

```
ffffffff81690e80-ffffffff81690ed4: queue_release_one_tty (STB_LOCAL)
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
