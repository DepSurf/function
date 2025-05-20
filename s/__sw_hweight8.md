# Function: <code>__sw_hweight8</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int __sw_hweight8(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffffffff81403490)
Location: lib/hweight.c:38
Inline: False
```
**Symbols:**

```
ffffffff81403490-ffffffff814034b8: __sw_hweight8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int __sw_hweight8(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffffffff8144b090)
Location: lib/hweight.c:40
Inline: False
```
**Symbols:**

```
ffffffff8144b090-ffffffff8144b0b6: __sw_hweight8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int __sw_hweight8(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffffffff81469a50)
Location: lib/hweight.c:40
Inline: False
```
**Symbols:**

```
ffffffff81469a50-ffffffff81469a76: __sw_hweight8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int __sw_hweight8(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffffffff8146f130)
Location: lib/hweight.c:40
Inline: False
```
**Symbols:**

```
ffffffff8146f130-ffffffff8146f156: __sw_hweight8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int __sw_hweight8(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffffffff8149b840)
Location: lib/hweight.c:41
Inline: False
```
**Symbols:**

```
ffffffff8149b840-ffffffff8149b866: __sw_hweight8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int __sw_hweight8(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffffffff814d0b10)
Location: lib/hweight.c:41
Inline: False
```
**Symbols:**

```
ffffffff814d0b10-ffffffff814d0b31: __sw_hweight8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int __sw_hweight8(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffffffff814e5440)
Location: lib/hweight.c:41
Inline: False
```
**Symbols:**

```
ffffffff814e5440-ffffffff814e5461: __sw_hweight8 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
unsigned int __sw_hweight8(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffff80001063ef30)
Location: lib/hweight.c:39
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_populate_lr
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_populate_lr
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
**Symbols:**

```
ffff80001063ef30-ffff80001063ef58: __sw_hweight8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int __sw_hweight8(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (c07e4668)
Location: lib/hweight.c:39
Inline: False
Direct callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
  - drivers/mtd/nand/raw/nand_base.c:nand_check_erased_buf
  - drivers/mtd/nand/raw/nand_base.c:nand_check_erased_buf
  - drivers/mtd/nand/raw/nand_base.c:nand_isbad_bbm
  - drivers/mtd/nand/raw/omap2.c:omap_elm_correct_data
  - drivers/mtd/nand/raw/omap2.c:omap_elm_correct_data
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
**Symbols:**

```
c07e4668-c07e469c: __sw_hweight8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int __sw_hweight8(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (c0000000007e8760)
Location: lib/hweight.c:39
Inline: False
```
**Symbols:**

```
c0000000007e8760-c0000000007e878c: __sw_hweight8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int __sw_hweight8(unsigned int w);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/hweight.c (ffffffe00046bdba)
Location: lib/hweight.c:39
Inline: False
Direct callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
**Symbols:**

```
ffffffe00046bdba-ffffffe00046bde6: __sw_hweight8 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
<b>Arch</b>
<ul>
</ul>
