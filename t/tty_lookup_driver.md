# Function: <code>tty_lookup_driver</code>

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
In drivers/tty/tty_io.c (ffffffff814e3dcc)
Location: drivers/tty/tty_io.c:1973
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff81535146)
Location: drivers/tty/tty_io.c:1971
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff81561871)
Location: drivers/tty/tty_io.c:1971
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
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
In drivers/tty/tty_io.c (ffffffff8157528a)
Location: drivers/tty/tty_io.c:1753
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d8840)
Location: drivers/tty/tty_io.c:1805
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff815d8840-ffffffff815d8902: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81610ca0)
Location: drivers/tty/tty_io.c:1823
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff81610ca0-ffffffff81610d66: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162daa0)
Location: drivers/tty/tty_io.c:1835
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff8162daa0-ffffffff8162db66: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81661650)
Location: drivers/tty/tty_io.c:1837
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff81661650-ffffffff81661735: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81683ca0)
Location: drivers/tty/tty_io.c:1837
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff81683ca0-ffffffff81683d85: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817368a0)
Location: drivers/tty/tty_io.c:1837
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff817368a0-ffffffff81736ab6: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81751da0)
Location: drivers/tty/tty_io.c:1921
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff81751da0-ffffffff81751fb6: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817359f0)
Location: drivers/tty/tty_io.c:1936
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff817359f0-ffffffff81735bfa: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b63b0)
Location: drivers/tty/tty_io.c:1930
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff817b63b0-ffffffff817b65ba: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f3660)
Location: drivers/tty/tty_io.c:1918
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff818f3660-ffffffff818f3879: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4bf40)
Location: drivers/tty/tty_io.c:1913
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff81a4bf40-ffffffff81a4c154: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a96160)
Location: drivers/tty/tty_io.c:1922
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff81a96160-ffffffff81a9638d: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae8a60)
Location: drivers/tty/tty_io.c:1920
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff81ae8a60-ffffffff81ae8c8d: tty_lookup_driver (STB_LOCAL)
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
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084fa28)
Location: drivers/tty/tty_io.c:1837
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffff80001084fa28-ffff80001084fb74: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095ba54)
Location: drivers/tty/tty_io.c:1837
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
c095ba54-c095bb70: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008efc20)
Location: drivers/tty/tty_io.c:1837
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
c0000000008efc20-c0000000008efdac: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052df08)
Location: drivers/tty/tty_io.c:1837
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffe00052df08-ffffffe00052e026: tty_lookup_driver (STB_LOCAL)
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
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81649720)
Location: drivers/tty/tty_io.c:1837
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff81649720-ffffffff81649805: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81629b80)
Location: drivers/tty/tty_io.c:1837
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff81629b80-ffffffff81629c65: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81677ae0)
Location: drivers/tty/tty_io.c:1837
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff81677ae0-ffffffff81677bc5: tty_lookup_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *tty_lookup_driver(dev_t device, struct file *filp, int *index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81692f80)
Location: drivers/tty/tty_io.c:1837
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
```
**Symbols:**

```
ffffffff81692f80-ffffffff81693065: tty_lookup_driver (STB_LOCAL)
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
