# Function: <code>apei_exec_ctx_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff814b2ae0)
Location: drivers/acpi/apei/apei-base.c:52
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_get_record_count
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_write
```
**Symbols:**

```
ffffffff814b2ae0-ffffffff814b2afa: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81502400)
Location: drivers/acpi/apei/apei-base.c:52
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff81502400-ffffffff8150241a: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff815265e0)
Location: drivers/acpi/apei/apei-base.c:52
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff815265e0-ffffffff815265fa: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81539510)
Location: drivers/acpi/apei/apei-base.c:52
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff81539510-ffffffff8153952a: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8159c070)
Location: drivers/acpi/apei/apei-base.c:52
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff8159c070-ffffffff8159c08a: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff815d3da0)
Location: drivers/acpi/apei/apei-base.c:52
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff815d3da0-ffffffff815d3dba: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff815ed550)
Location: drivers/acpi/apei/apei-base.c:52
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff815ed550-ffffffff815ed56a: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8161f300)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff8161f300-ffffffff8161f31a: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81640de0)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff81640de0-ffffffff81640dfa: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff816ede80)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:__erst_clear_from_storage
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff816ede80-ffffffff816ede9a: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8170b490)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:__erst_clear_from_storage
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff8170b490-ffffffff8170b4aa: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff816ecae0)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff816ecae0-ffffffff816ecafa: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81766c20)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff81766c20-ffffffff81766c3a: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8189b230)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff8189b230-ffffffff8189b259: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff819e3830)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff819e3830-ffffffff819e3859: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81a2be50)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff81a2be50-ffffffff81a2be79: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81a77020)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:__erst_record_id_cache_add_one
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff81a77020-ffffffff81a77049: apei_exec_ctx_init (STB_GLOBAL)
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
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffff8000107aba10)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffff8000107aba10-ffff8000107aba64: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff815fd1f0)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff815fd1f0-ffffffff815fd20a: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff81634c20)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff81634c20-ffffffff81634c3a: apei_exec_ctx_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void apei_exec_ctx_init(struct apei_exec_context *ctx, struct apei_exec_ins_type *ins_table, u32 instructions, struct acpi_whea_header *action_table, u32 entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/apei-base.c (ffffffff8164ef30)
Location: drivers/acpi/apei/apei-base.c:44
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_get_record_id_next
  - drivers/acpi/apei/erst.c:erst_get_record_count
```
**Symbols:**

```
ffffffff8164ef30-ffffffff8164ef4a: apei_exec_ctx_init (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
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
