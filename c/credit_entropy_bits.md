# Function: <code>credit_entropy_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81512420)
Location: drivers/char/random.c:616
Inline: False
Direct callers:
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
```
**Symbols:**

```
ffffffff81512420-ffffffff81512763: credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81566820)
Location: drivers/char/random.c:642
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff81566820-ffffffff81566a93: credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81592f80)
Location: drivers/char/random.c:642
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff81592f80-ffffffff815931f3: credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a6d80)
Location: drivers/char/random.c:634
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff815a6d80-ffffffff815a6ffc: credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160d680)
Location: drivers/char/random.c:633
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff8160d680-ffffffff8160d8fe: credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:645
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff81647190-ffffffff816473ec: credit_entropy_bits (STB_LOCAL)
ffffffff816491fb-ffffffff81649235: credit_entropy_bits.cold.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:644
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff81665630-ffffffff8166588c: credit_entropy_bits (STB_LOCAL)
ffffffff81667507-ffffffff81667541: credit_entropy_bits.cold.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:712
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff8169b270-ffffffff8169b501: credit_entropy_bits (STB_LOCAL)
ffffffff8169cfa2-ffffffff8169cfe9: credit_entropy_bits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:712
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff816bdf90-ffffffff816be221: credit_entropy_bits (STB_LOCAL)
ffffffff816bfd06-ffffffff816bfd41: credit_entropy_bits.cold (STB_LOCAL)
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
In drivers/char/random.c (0)
Location: drivers/char/random.c:661
Inline: True
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff817726b0-ffffffff817727e8: credit_entropy_bits.constprop.0 (STB_LOCAL)
ffffffff81773bd6-ffffffff81773bfa: credit_entropy_bits.constprop.0.cold (STB_LOCAL)
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
In drivers/char/random.c (0)
Location: drivers/char/random.c:661
Inline: True
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff8178d720-ffffffff8178d840: credit_entropy_bits.constprop.0 (STB_LOCAL)
ffffffff81c0856b-ffffffff81c0858f: credit_entropy_bits.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:660
Inline: True
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff81771080-ffffffff817711a1: credit_entropy_bits.constprop.0 (STB_LOCAL)
ffffffff81bfa175-ffffffff81bfa199: credit_entropy_bits.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:661
Inline: True
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff817f6c00-ffffffff817f6d30: credit_entropy_bits.constprop.0 (STB_LOCAL)
ffffffff81cfaa7f-ffffffff81cfaafd: credit_entropy_bits.constprop.0.cold (STB_LOCAL)
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
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108aead8)
Location: drivers/char/random.c:712
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffff8000108aead8-ffff8000108aedf8: credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09aa9d4)
Location: drivers/char/random.c:712
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
c09aa9d4-c09aad3c: credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000946ee0)
Location: drivers/char/random.c:712
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
c000000000946ee0-c000000000947390: credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe000562676)
Location: drivers/char/random.c:712
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffe000562676-ffffffe000562966: credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:712
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff81683a00-ffffffff81683c91: credit_entropy_bits (STB_LOCAL)
ffffffff81685756-ffffffff81685791: credit_entropy_bits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:712
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff81661680-ffffffff81661911: credit_entropy_bits (STB_LOCAL)
ffffffff816633f6-ffffffff81663431: credit_entropy_bits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:712
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff816b1dd0-ffffffff816b2061: credit_entropy_bits (STB_LOCAL)
ffffffff816b3b46-ffffffff816b3b81: credit_entropy_bits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void credit_entropy_bits(struct entropy_store *r, int nbits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:712
Inline: False
Direct callers:
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:entropy_timer
  - drivers/char/random.c:_xfer_secondary_pool
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:add_timer_randomness
```
**Symbols:**

```
ffffffff816cc270-ffffffff816cc516: credit_entropy_bits (STB_LOCAL)
ffffffff816ce0a6-ffffffff816ce0e1: credit_entropy_bits.cold (STB_LOCAL)
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
