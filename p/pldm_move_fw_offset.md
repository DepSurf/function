# Function: <code>pldm_move_fw_offset</code>

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
In <code>5.0</code>: Absent ⚠️
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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv *data, size_t bytes_to_move);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff8160b258)
Location: lib/pldmfw/pldmfw.c:91
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
Direct callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_image
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
**Symbols:**

```
ffffffff8160af40-ffffffff8160af92: pldm_move_fw_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv *data, size_t bytes_to_move);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff815ee348)
Location: lib/pldmfw/pldmfw.c:91
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
Direct callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
**Symbols:**

```
ffffffff815ee020-ffffffff815ee072: pldm_move_fw_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv *data, size_t bytes_to_move);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff8165b3f8)
Location: lib/pldmfw/pldmfw.c:91
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
Direct callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
**Symbols:**

```
ffffffff8165b0f0-ffffffff8165b13f: pldm_move_fw_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv *data, size_t bytes_to_move);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff81774278)
Location: lib/pldmfw/pldmfw.c:91
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
Direct callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
**Symbols:**

```
ffffffff81773f30-ffffffff81773fb5: pldm_move_fw_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv *data, size_t bytes_to_move);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff818a4d68)
Location: lib/pldmfw/pldmfw.c:91
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
Direct callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
**Symbols:**

```
ffffffff818a4a00-ffffffff818a4a85: pldm_move_fw_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv *data, size_t bytes_to_move);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff818e7600)
Location: lib/pldmfw/pldmfw.c:91
Inline: False
Direct callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
**Symbols:**

```
ffffffff818e7600-ffffffff818e7685: pldm_move_fw_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pldm_move_fw_offset(struct pldmfw_priv *data, size_t bytes_to_move);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff8192e640)
Location: lib/pldmfw/pldmfw.c:91
Inline: False
Direct callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
  - lib/pldmfw/pldmfw.c:pldm_parse_header
```
**Symbols:**

```
ffffffff8192e640-ffffffff8192e6c5: pldm_move_fw_offset (STB_LOCAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
