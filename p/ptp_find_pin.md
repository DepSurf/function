# Function: <code>ptp_find_pin</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff817dee80)
Location: drivers/ptp/ptp_clock.c:358
Inline: False
```
**Symbols:**

```
ffffffff817dee80-ffffffff817def0c: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8180a2c0)
Location: drivers/ptp/ptp_clock.c:360
Inline: False
```
**Symbols:**

```
ffffffff8180a2c0-ffffffff8180a34c: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8184bfa0)
Location: drivers/ptp/ptp_clock.c:348
Inline: False
```
**Symbols:**

```
ffffffff8184bfa0-ffffffff8184c02c: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8187d7a0)
Location: drivers/ptp/ptp_clock.c:343
Inline: False
```
**Symbols:**

```
ffffffff8187d7a0-ffffffff8187d82c: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8194c197)
Location: drivers/ptp/ptp_clock.c:352
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked
```
**Symbols:**

```
ffffffff8194b980-ffffffff8194b9d5: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81951ba7)
Location: drivers/ptp/ptp_clock.c:352
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked
```
**Symbols:**

```
ffffffff81951390-ffffffff819513e5: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81935a27)
Location: drivers/ptp/ptp_clock.c:352
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked
```
**Symbols:**

```
ffffffff81935210-ffffffff81935263: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff819d8fb7)
Location: drivers/ptp/ptp_clock.c:376
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked
```
**Symbols:**

```
ffffffff819d85e0-ffffffff819d8633: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81b3c738)
Location: drivers/ptp/ptp_clock.c:406
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked
```
**Symbols:**

```
ffffffff81b3ba30-ffffffff81b3ba94: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81cd26e8)
Location: drivers/ptp/ptp_clock.c:403
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked
```
**Symbols:**

```
ffffffff81cd1910-ffffffff81cd1974: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81d3a168)
Location: drivers/ptp/ptp_clock.c:407
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked
```
**Symbols:**

```
ffffffff81d39350-ffffffff81d393b4: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81df0718)
Location: drivers/ptp/ptp_clock.c:447
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_find_pin_unlocked
```
**Symbols:**

```
ffffffff81def5f0-ffffffff81def654: ptp_find_pin (STB_GLOBAL)
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
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffff800010ac73b0)
Location: drivers/ptp/ptp_clock.c:343
Inline: False
```
**Symbols:**

```
ffff800010ac73b0-ffff800010ac7464: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c0ba6e18)
Location: drivers/ptp/ptp_clock.c:343
Inline: False
```
**Symbols:**

```
c0ba6e18-c0ba6eb4: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c000000000ba8810)
Location: drivers/ptp/ptp_clock.c:343
Inline: False
```
**Symbols:**

```
c000000000ba8810-c000000000ba8908: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffe0006c5aa0)
Location: drivers/ptp/ptp_clock.c:343
Inline: False
```
**Symbols:**

```
ffffffe0006c5aa0-ffffffe0006c5b28: ptp_find_pin (STB_GLOBAL)
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
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81825d10)
Location: drivers/ptp/ptp_clock.c:343
Inline: False
```
**Symbols:**

```
ffffffff81825d10-ffffffff81825d9c: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff817ed3a0)
Location: drivers/ptp/ptp_clock.c:343
Inline: False
```
**Symbols:**

```
ffffffff817ed3a0-ffffffff817ed42c: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81872c50)
Location: drivers/ptp/ptp_clock.c:343
Inline: False
```
**Symbols:**

```
ffffffff81872c50-ffffffff81872cdc: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptp_find_pin(struct ptp_clock *ptp, enum ptp_pin_function func, unsigned int chan);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8188e600)
Location: drivers/ptp/ptp_clock.c:343
Inline: False
```
**Symbols:**

```
ffffffff8188e600-ffffffff8188e68c: ptp_find_pin (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
