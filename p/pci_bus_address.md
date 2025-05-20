# Function: <code>pci_bus_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8151d8fc)
Location: include/linux/pci.h:1173
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8151fb83)
Location: include/linux/pci.h:1173
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81520378)
Location: include/linux/pci.h:1173
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81522743)
Location: include/linux/pci.h:1173
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff8152320a)
Location: include/linux/pci.h:1173
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff815706cc)
Location: include/linux/pci.h:1176
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff815729e2)
Location: include/linux/pci.h:1176
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff815731d8)
Location: include/linux/pci.h:1176
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815755ed)
Location: include/linux/pci.h:1176
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff8157614a)
Location: include/linux/pci.h:1176
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8159cd8c)
Location: include/linux/pci.h:1207
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8159f1a6)
Location: include/linux/pci.h:1207
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8159f848)
Location: include/linux/pci.h:1207
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815a1c7a)
Location: include/linux/pci.h:1207
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff815a27da)
Location: include/linux/pci.h:1207
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff815b0e4c)
Location: include/linux/pci.h:1224
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff815b3057)
Location: include/linux/pci.h:1224
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff815b38c1)
Location: include/linux/pci.h:1224
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff815b5840)
Location: include/linux/pci.h:1224
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff815b633a)
Location: include/linux/pci.h:1224
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816179ec)
Location: include/linux/pci.h:1249
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81619c97)
Location: include/linux/pci.h:1249
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8161a511)
Location: include/linux/pci.h:1249
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8161c894)
Location: include/linux/pci.h:1249
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff8161d04a)
Location: include/linux/pci.h:1249
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81651512)
Location: include/linux/pci.h:1251
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81653916)
Location: include/linux/pci.h:1251
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816541c9)
Location: include/linux/pci.h:1251
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81656474)
Location: include/linux/pci.h:1251
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81656cfc)
Location: include/linux/pci.h:1251
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8166f6e2)
Location: include/linux/pci.h:1286
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81671b16)
Location: include/linux/pci.h:1286
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816723c9)
Location: include/linux/pci.h:1286
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816742f3)
Location: include/linux/pci.h:1286
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81674dfc)
Location: include/linux/pci.h:1286
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816a5202)
Location: include/linux/pci.h:1346
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816a7839)
Location: include/linux/pci.h:1346
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816a7e49)
Location: include/linux/pci.h:1346
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816aa461)
Location: include/linux/pci.h:1346
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff816aa8ec)
Location: include/linux/pci.h:1346
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816c7f32)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816ca579)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816cab89)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816cd1a1)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff816cd62c)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8177c6c2)
Location: include/linux/pci.h:1363
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8177f128)
Location: include/linux/pci.h:1363
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/char/agp/intel-agp.c (ffffffff8177f817)
Location: include/linux/pci.h:1363
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff8178219b)
Location: include/linux/pci.h:1363
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff817824ec)
Location: include/linux/pci.h:1363
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81795812)
Location: include/linux/pci.h:1371
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81c097fc)
Location: include/linux/pci.h:1371
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/char/agp/intel-agp.c (ffffffff81797737)
Location: include/linux/pci.h:1371
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81c0a103)
Location: include/linux/pci.h:1371
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff81799c6c)
Location: include/linux/pci.h:1371
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff817784d2)
Location: include/linux/pci.h:1387
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81bfb1a0)
Location: include/linux/pci.h:1387
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/char/agp/intel-agp.c (ffffffff8177a417)
Location: include/linux/pci.h:1387
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81bfbb5f)
Location: include/linux/pci.h:1387
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff8177c7fc)
Location: include/linux/pci.h:1387
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff817fdf72)
Location: include/linux/pci.h:1429
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81cfbd6b)
Location: include/linux/pci.h:1429
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/char/agp/intel-agp.c (ffffffff818004b7)
Location: include/linux/pci.h:1429
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81cfc764)
Location: include/linux/pci.h:1429
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff818029cc)
Location: include/linux/pci.h:1429
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8193d501)
Location: include/linux/pci.h:1456
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81ec452b)
Location: include/linux/pci.h:1456
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/char/agp/intel-agp.c (ffffffff8193f91f)
Location: include/linux/pci.h:1456
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81ec4f82)
Location: include/linux/pci.h:1456
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff8194220b)
Location: include/linux/pci.h:1456
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff8191c1ec)
Location: include/linux/pci.h:1478
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/char/agp/generic.c (ffffffff81a9e3a1)
Location: include/linux/pci.h:1478
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aa0873)
Location: include/linux/pci.h:1478
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/char/agp/intel-agp.c (ffffffff81aa14af)
Location: include/linux/pci.h:1478
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aa3c38)
Location: include/linux/pci.h:1478
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff81aa473b)
Location: include/linux/pci.h:1478
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff8195f806)
Location: include/linux/pci.h:1547
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/char/agp/generic.c (ffffffff81ae9d41)
Location: include/linux/pci.h:1547
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aec18b)
Location: include/linux/pci.h:1547
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/char/agp/intel-agp.c (ffffffff81aecd8f)
Location: include/linux/pci.h:1547
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81aef518)
Location: include/linux/pci.h:1547
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff81af005b)
Location: include/linux/pci.h:1547
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff819a8e6e)
Location: include/linux/pci.h:1576
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/char/agp/generic.c (ffffffff81b3d1d1)
Location: include/linux/pci.h:1576
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81b3f6cb)
Location: include/linux/pci.h:1576
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:fix_northbridge
```
```
In drivers/char/agp/intel-agp.c (ffffffff81b402cf)
Location: include/linux/pci.h:1576
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81b42a5d)
Location: include/linux/pci.h:1576
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff81b4359b)
Location: include/linux/pci.h:1576
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (c0000000009556ac)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8168d982)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8168ffc9)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816905d9)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff81692bf1)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff8169307c)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8166b372)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8166d9b9)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8166dfc9)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816705e1)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff81670a6c)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816bbbf2)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816be239)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816be849)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816c0e61)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff816c12ec)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816d61c2)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp3_generic_configure
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816d8809)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816d8e19)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
```
```
In drivers/char/agp/intel-gtt.c (ffffffff816db431)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
```
```
In drivers/char/agp/via-agp.c (ffffffff816db8bc)
Location: include/linux/pci.h:1338
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
</details>
</li>
</ul>

## Differences
