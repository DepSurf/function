# Function: <code>has_uuid_at_pos</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff8159e429)
Location: drivers/nvdimm/namespace_devs.c:1444
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
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
In drivers/nvdimm/namespace_devs.c (ffffffff815f446e)
Location: drivers/nvdimm/namespace_devs.c:1486
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8161ebb0)
Location: drivers/nvdimm/namespace_devs.c:1594
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8161ebb0-ffffffff8161ed01: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81635040)
Location: drivers/nvdimm/namespace_devs.c:1752
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81635040-ffffffff81635250: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169d9c0)
Location: drivers/nvdimm/namespace_devs.c:1761
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff8169d9c0-ffffffff8169dbd0: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816d94b0)
Location: drivers/nvdimm/namespace_devs.c:1758
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff816d94b0-ffffffff816d96ad: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fb440)
Location: drivers/nvdimm/namespace_devs.c:1784
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
**Symbols:**

```
ffffffff816fb440-ffffffff816fb644: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81734ea0)
Location: drivers/nvdimm/namespace_devs.c:1791
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81734ea0-ffffffff817350a4: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81758c30)
Location: drivers/nvdimm/namespace_devs.c:1791
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81758c30-ffffffff81758e34: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81818530)
Location: drivers/nvdimm/namespace_devs.c:1834
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81818530-ffffffff81818734: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81827660)
Location: drivers/nvdimm/namespace_devs.c:1834
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81827660-ffffffff81827864: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8180ab90)
Location: drivers/nvdimm/namespace_devs.c:1834
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8180ab90-ffffffff8180ad94: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81894060)
Location: drivers/nvdimm/namespace_devs.c:1834
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81894060-ffffffff818941c9: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, const uuid_t *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1561
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff819df230-ffffffff819df479: has_uuid_at_pos (STB_LOCAL)
ffffffff81ed37b7-ffffffff81ed3966: has_uuid_at_pos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, const uuid_t *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1553
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81b5b160-ffffffff81b5b3ad: has_uuid_at_pos (STB_LOCAL)
ffffffff8209a9ab-ffffffff8209ab5a: has_uuid_at_pos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, const uuid_t *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1553
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81badcf0-ffffffff81badf30: has_uuid_at_pos (STB_LOCAL)
ffffffff8211b949-ffffffff8211ba28: has_uuid_at_pos.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, const uuid_t *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:1562
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81c02060-ffffffff81c022a0: has_uuid_at_pos (STB_LOCAL)
ffffffff821f97d0-ffffffff821f98af: has_uuid_at_pos.cold (STB_LOCAL)
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
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095a338)
Location: drivers/nvdimm/namespace_devs.c:1791
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffff80001095a338-ffff80001095a56c: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0a050)
Location: drivers/nvdimm/namespace_devs.c:1791
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
c000000000a0a050-c000000000a0a308: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c824c)
Location: drivers/nvdimm/namespace_devs.c:1791
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffe0005c824c-ffffffe0005c83d0: has_uuid_at_pos (STB_LOCAL)
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
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8170d320)
Location: drivers/nvdimm/namespace_devs.c:1791
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8170d320-ffffffff8170d524: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816e0da0)
Location: drivers/nvdimm/namespace_devs.c:1791
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff816e0da0-ffffffff816e0fa4: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8174c0f0)
Location: drivers/nvdimm/namespace_devs.c:1791
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8174c0f0-ffffffff8174c2f4: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region *nd_region, u8 *uuid, u64 cookie, u16 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81767570)
Location: drivers/nvdimm/namespace_devs.c:1791
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81767570-ffffffff81767774: has_uuid_at_pos (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 *uuid</code> ➡️ <code>const uuid_t *uuid</code>
</li>
</ul>
</details>
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
