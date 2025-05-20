# Function: <code>ima_template_desc_buf</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_buf();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81537da0)
Location: security/integrity/ima/ima_template.c:256
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff81537da0-ffffffff81537de1: ima_template_desc_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_buf();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff815403f0)
Location: security/integrity/ima/ima_template.c:256
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff815403f0-ffffffff81540431: ima_template_desc_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_buf();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8159fc10)
Location: security/integrity/ima/ima_template.c:280
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff8159fc10-ffffffff8159fc51: ima_template_desc_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ima_template_desc *ima_template_desc_buf();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81645760)
Location: security/integrity/ima/ima_template.c:284
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_template.c:ima_init_template
```
**Symbols:**

```
ffffffff81645760-ffffffff81645825: ima_template_desc_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ima_template_desc *ima_template_desc_buf();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff83ed7085)
Location: security/integrity/ima/ima_template.c:284
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_init_template
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
```
**Symbols:**

```
ffffffff816fdc60-ffffffff816fdd25: ima_template_desc_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct ima_template_desc *ima_template_desc_buf();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff836fc235)
Location: security/integrity/ima/ima_template.c:284
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_init_template
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
```
**Symbols:**

```
ffffffff81737c80-ffffffff81737d45: ima_template_desc_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct ima_template_desc *ima_template_desc_buf();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8392f825)
Location: security/integrity/ima/ima_template.c:284
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_init_template
Direct callers:
  - security/integrity/ima/ima_main.c:process_buffer_measurement
```
**Symbols:**

```
ffffffff81778770-ffffffff81778835: ima_template_desc_buf (STB_GLOBAL)
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
