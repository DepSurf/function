# Function: <code>init_std_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81513d70)
Location: drivers/char/random.c:1367
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff81513d70-ffffffff81513e5e: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815660b0)
Location: drivers/char/random.c:1629
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff815660b0-ffffffff815661a6: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81592810)
Location: drivers/char/random.c:1629
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff81592810-ffffffff81592906: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a6aa0)
Location: drivers/char/random.c:1657
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff815a6aa0-ffffffff815a6bac: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160d3a0)
Location: drivers/char/random.c:1656
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff8160d3a0-ffffffff8160d4ac: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81646430)
Location: drivers/char/random.c:1761
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff81646430-ffffffff81646526: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81665080)
Location: drivers/char/random.c:1786
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff81665080-ffffffff81665176: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff828f9dc2)
Location: drivers/char/random.c:1868
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff828f9dc2-ffffffff828f9e96: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff82902cc5)
Location: drivers/char/random.c:1929
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff82902cc5-ffffffff82902d99: init_std_data (STB_LOCAL)
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
In drivers/char/random.c (ffffffff82d19a93)
Location: drivers/char/random.c:1774
Inline: True
Direct callers:
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff82d19a93-ffffffff82d19b4e: init_std_data.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff83007797)
Location: drivers/char/random.c:1773
Inline: True
Direct callers:
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff83007797-ffffffff8300784e: init_std_data.constprop.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff83212312)
Location: drivers/char/random.c:1749
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
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
In drivers/char/random.c (ffffffff832fb526)
Location: drivers/char/random.c:1769
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff800011495d14)
Location: drivers/char/random.c:1929
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffff800011495d14-ffff800011495df0: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c1596074)
Location: drivers/char/random.c:1929
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
c1596074-c1596164: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c0000000013a8314)
Location: drivers/char/random.c:1929
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
c0000000013a8314-c0000000013a8434: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe00002f938)
Location: drivers/char/random.c:1929
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffe00002f938-ffffffe00002f9c2: init_std_data (STB_LOCAL)
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
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff828ea4ac)
Location: drivers/char/random.c:1929
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff828ea4ac-ffffffff828ea580: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff828e1939)
Location: drivers/char/random.c:1929
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff828e1939-ffffffff828e1a0d: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff828fdfe8)
Location: drivers/char/random.c:1929
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff828fdfe8-ffffffff828fe0bc: init_std_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void init_std_data(struct entropy_store *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff82903d27)
Location: drivers/char/random.c:1929
Inline: False
Direct callers:
  - drivers/char/random.c:rand_initialize
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff82903d27-ffffffff82903dfb: init_std_data (STB_LOCAL)
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
