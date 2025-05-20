# Function: <code>spi_add_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e6c60)
Location: drivers/spi/spi.c:497
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_new_device
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff815e6c60-ffffffff815e6e2f: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81645250)
Location: drivers/spi/spi.c:500
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81645250-ffffffff81645428: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81676350)
Location: drivers/spi/spi.c:501
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81676350-ffffffff81676528: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168a880)
Location: drivers/spi/spi.c:503
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff8168a880-ffffffff8168aa60: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f40a0)
Location: drivers/spi/spi.c:507
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff816f40a0-ffffffff816f4271: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81730ae0)
Location: drivers/spi/spi.c:511
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81730ae0-ffffffff81730cd2: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817536b0)
Location: drivers/spi/spi.c:551
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff817536b0-ffffffff817538a2: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:554
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff8179279a-ffffffff81792821: spi_add_device.cold (STB_LOCAL)
ffffffff8178ea90-ffffffff8178ec26: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:555
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff817b633c-ffffffff817b63c3: spi_add_device.cold (STB_LOCAL)
ffffffff817b2650-ffffffff817b27e6: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:561
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff8187d2c5-ffffffff8187d34c: spi_add_device.cold (STB_LOCAL)
ffffffff8187aba0-ffffffff8187ad43: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:570
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81c18d45-ffffffff81c18dcc: spi_add_device.cold (STB_LOCAL)
ffffffff81889890-ffffffff81889a33: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:572
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81c0aab0-ffffffff81c0ab5d: spi_add_device.cold (STB_LOCAL)
ffffffff8186c1a0-ffffffff8186c34f: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:654
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81d0fc78-ffffffff81d0fc97: spi_add_device.cold (STB_LOCAL)
ffffffff818fc1c0-ffffffff818fc229: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:626
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81eda9a3-ffffffff81eda9c2: spi_add_device.cold (STB_LOCAL)
ffffffff81a4d860-ffffffff81a4d8d1: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd7d30)
Location: drivers/spi/spi.c:688
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81bd7d30-ffffffff81bd7db7: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2e760)
Location: drivers/spi/spi.c:689
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81c2e760-ffffffff81c2e7e7: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81ce20a7)
Location: drivers/spi/spi.c:733
Inline: True
Inline callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81ce1350-ffffffff81ce1399: spi_add_device (STB_GLOBAL)
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
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c2958)
Location: drivers/spi/spi.c:555
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffff8000109c2958-ffff8000109c2b58: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0aafba8)
Location: drivers/spi/spi.c:555
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
c0aafba8-c0aafd40: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a86680)
Location: drivers/spi/spi.c:555
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
c000000000a86680-c000000000a868b4: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe00061668a)
Location: drivers/spi/spi.c:555
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffe00061668a-ffffffe000616822: spi_add_device (STB_GLOBAL)
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
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:555
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff8177ae1c-ffffffff8177aea3: spi_add_device.cold (STB_LOCAL)
ffffffff81777130-ffffffff817772c6: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:555
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff8175abcc-ffffffff8175ac53: spi_add_device.cold (STB_LOCAL)
ffffffff81756ee0-ffffffff81757076: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:555
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff817ab1bc-ffffffff817ab243: spi_add_device.cold (STB_LOCAL)
ffffffff817a74d0-ffffffff817a7666: spi_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int spi_add_device(struct spi_device *spi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:555
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff817c514c-ffffffff817c51d3: spi_add_device.cold (STB_LOCAL)
ffffffff817c1350-ffffffff817c14e6: spi_add_device (STB_GLOBAL)
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
