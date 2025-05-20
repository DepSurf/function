# Function: <code>cec_get_edid_phys_addr</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 *edid, unsigned int size, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81803ac0)
Location: drivers/media/cec/cec-adap.c:65
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff81803ac0-ffffffff81803c06: cec_get_edid_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 *edid, unsigned int size, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81845040)
Location: drivers/media/cec/cec-adap.c:68
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff81845040-ffffffff8184518b: cec_get_edid_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 *edid, unsigned int size, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81876920)
Location: drivers/media/cec/cec-adap.c:68
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff81876920-ffffffff81876a6b: cec_get_edid_phys_addr (STB_GLOBAL)
```
</details>
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
u16 cec_get_edid_phys_addr(const u8 *edid, unsigned int size, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abe238)
Location: drivers/media/cec/cec-adap.c:68
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffff800010abe238-ffff800010abe3a0: cec_get_edid_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 *edid, unsigned int size, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0b9ff7c)
Location: drivers/media/cec/cec-adap.c:68
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
c0b9ff7c-c0ba00d0: cec_get_edid_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 *edid, unsigned int size, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000b9f7d0)
Location: drivers/media/cec/cec-adap.c:68
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
c000000000b9f7d0-c000000000b9f954: cec_get_edid_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 *edid, unsigned int size, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006bfe1a)
Location: drivers/media/cec/cec-adap.c:68
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffe0006bfe1a-ffffffe0006bff84: cec_get_edid_phys_addr (STB_GLOBAL)
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
u16 cec_get_edid_phys_addr(const u8 *edid, unsigned int size, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8181ee90)
Location: drivers/media/cec/cec-adap.c:68
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff8181ee90-ffffffff8181efdb: cec_get_edid_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 *edid, unsigned int size, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e6530)
Location: drivers/media/cec/cec-adap.c:68
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff817e6530-ffffffff817e667b: cec_get_edid_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 *edid, unsigned int size, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186bdd0)
Location: drivers/media/cec/cec-adap.c:68
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff8186bdd0-ffffffff8186bf1b: cec_get_edid_phys_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u16 cec_get_edid_phys_addr(const u8 *edid, unsigned int size, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81885d60)
Location: drivers/media/cec/cec-adap.c:68
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid
  - drivers/media/cec/cec-notifier.c:cec_notifier_set_phys_addr_from_edid
```
**Symbols:**

```
ffffffff81885d60-ffffffff81885eab: cec_get_edid_phys_addr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
