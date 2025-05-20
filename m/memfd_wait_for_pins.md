# Function: <code>memfd_wait_for_pins</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812941a0)
Location: mm/memfd.c:73
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
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
In mm/memfd.c (ffffffff812a8e5e)
Location: mm/memfd.c:65
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812c52b0)
Location: mm/memfd.c:65
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812c52b0-ffffffff812c56b0: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812d6c40)
Location: mm/memfd.c:66
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812d6c40-ffffffff812d70be: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff8130bf20)
Location: mm/memfd.c:66
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff8130bf20-ffffffff8130c203: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff81317de0)
Location: mm/memfd.c:66
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff81317de0-ffffffff813180c3: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff8131dfd0)
Location: mm/memfd.c:66
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff8131dfd0-ffffffff8131e2be: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff8136b3b0)
Location: mm/memfd.c:74
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff8136b3b0-ffffffff8136b68b: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff813e9440)
Location: mm/memfd.c:74
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff813e9440-ffffffff813e97d7: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff81471420)
Location: mm/memfd.c:74
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff81471420-ffffffff814717e6: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memfd.c (0)
Location: mm/memfd.c:75
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff814a5940-ffffffff814a5cf1: memfd_wait_for_pins (STB_LOCAL)
ffffffff820e7f86-ffffffff820e7f9f: memfd_wait_for_pins.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memfd.c (0)
Location: mm/memfd.c:75
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff814d68f0-ffffffff814d6c8e: memfd_wait_for_pins (STB_LOCAL)
ffffffff821c4cc5-ffffffff821c4cde: memfd_wait_for_pins.cold (STB_LOCAL)
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
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffff80001037bbe8)
Location: mm/memfd.c:66
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffff80001037bbe8-ffff80001037c138: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (c0566978)
Location: mm/memfd.c:66
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
c0566978-c0566db0: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (c000000000470fe0)
Location: mm/memfd.c:66
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
c000000000470fe0-c00000000047164c: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffe000252386)
Location: mm/memfd.c:66
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffe000252386-ffffffe000252868: memfd_wait_for_pins (STB_LOCAL)
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
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812cf220)
Location: mm/memfd.c:66
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812cf220-ffffffff812cf69e: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812bfeb0)
Location: mm/memfd.c:66
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812bfeb0-ffffffff812c0316: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812cd030)
Location: mm/memfd.c:66
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812cd030-ffffffff812cd4ae: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int memfd_wait_for_pins(struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812dddd0)
Location: mm/memfd.c:66
Inline: False
Direct callers:
  - mm/memfd.c:memfd_fcntl
```
**Symbols:**

```
ffffffff812dddd0-ffffffff812de2b8: memfd_wait_for_pins (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
