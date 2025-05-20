# Function: <code>pldm_send_component_tables</code>

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
int pldm_send_component_tables(struct pldmfw_priv *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff8160aaf0)
Location: lib/pldmfw/pldmfw.c:737
Inline: False
Direct callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
**Symbols:**

```
ffffffff8160aaf0-ffffffff8160ab94: pldm_send_component_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff815ee8d7)
Location: lib/pldmfw/pldmfw.c:737
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff8165b987)
Location: lib/pldmfw/pldmfw.c:737
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff81774821)
Location: lib/pldmfw/pldmfw.c:737
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pldm_send_component_tables(struct pldmfw_priv *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff818a4670)
Location: lib/pldmfw/pldmfw.c:737
Inline: False
Direct callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
**Symbols:**

```
ffffffff818a4670-ffffffff818a472a: pldm_send_component_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pldm_send_component_tables(struct pldmfw_priv *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff818e74b0)
Location: lib/pldmfw/pldmfw.c:737
Inline: False
Direct callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
**Symbols:**

```
ffffffff818e74b0-ffffffff818e756a: pldm_send_component_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pldm_send_component_tables(struct pldmfw_priv *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/pldmfw/pldmfw.c (ffffffff8192e4f0)
Location: lib/pldmfw/pldmfw.c:737
Inline: False
Direct callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
```
**Symbols:**

```
ffffffff8192e4f0-ffffffff8192e5aa: pldm_send_component_tables (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
