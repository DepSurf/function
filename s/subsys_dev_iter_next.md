# Function: <code>subsys_dev_iter_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81549a60)
Location: drivers/base/bus.c:1101
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_register
  - drivers/base/bus.c:subsys_interface_unregister
```
**Symbols:**

```
ffffffff81549a60-ffffffff81549a94: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8159b6b0)
Location: drivers/base/bus.c:1096
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff8159b6b0-ffffffff8159b6e4: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815c9c10)
Location: drivers/base/bus.c:1096
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff815c9c10-ffffffff815c9c44: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815de950)
Location: drivers/base/bus.c:1055
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff815de950-ffffffff815de984: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81645980)
Location: drivers/base/bus.c:1055
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff81645980-ffffffff816459b4: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81680de0)
Location: drivers/base/bus.c:1053
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff81680de0-ffffffff81680e14: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a0870)
Location: drivers/base/bus.c:1060
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff816a0870-ffffffff816a08a2: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816d97b0)
Location: drivers/base/bus.c:1034
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff816d97b0-ffffffff816d97e2: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fd7b0)
Location: drivers/base/bus.c:1010
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff816fd7b0-ffffffff816fd7e2: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b7684)
Location: drivers/base/bus.c:1011
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff817b7020-ffffffff817b7055: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817cc3a4)
Location: drivers/base/bus.c:1011
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff817cbd50-ffffffff817cbd85: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817afd19)
Location: drivers/base/bus.c:994
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff817af6c0-ffffffff817af6f5: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81838fd9)
Location: drivers/base/bus.c:990
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff81838920-ffffffff81838955: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8197b5e1)
Location: drivers/base/bus.c:992
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff8197adc0-ffffffff8197adfd: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81ae8681)
Location: drivers/base/bus.c:992
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff81ae7d40-ffffffff81ae7d7d: subsys_dev_iter_next (STB_GLOBAL)
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
In drivers/base/bus.c (ffffffff81b36824)
Location: drivers/base/bus.c:1100
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
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
In drivers/base/bus.c (ffffffff81b8e244)
Location: drivers/base/bus.c:1100
Inline: True
Inline callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
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
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e8410)
Location: drivers/base/bus.c:1010
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffff8000108e8410-ffff8000108e845c: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d6820)
Location: drivers/base/bus.c:1010
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
c09d6820-c09d6868: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c00000000097e7d0)
Location: drivers/base/bus.c:1010
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
c00000000097e7d0-c00000000097e844: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057c67e)
Location: drivers/base/bus.c:1010
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffe00057c67e-ffffffe00057c6b8: subsys_dev_iter_next (STB_GLOBAL)
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
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c2fa0)
Location: drivers/base/bus.c:1010
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff816c2fa0-ffffffff816c2fd2: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169e250)
Location: drivers/base/bus.c:1010
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff8169e250-ffffffff8169e282: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f1470)
Location: drivers/base/bus.c:1010
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff816f1470-ffffffff816f14a2: subsys_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *subsys_dev_iter_next(struct subsys_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170bcb0)
Location: drivers/base/bus.c:1010
Inline: False
Direct callers:
  - drivers/base/bus.c:subsys_interface_unregister
  - drivers/base/bus.c:subsys_interface_register
```
**Symbols:**

```
ffffffff8170bcb0-ffffffff8170bce2: subsys_dev_iter_next (STB_GLOBAL)
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
