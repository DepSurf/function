# Function: <code>acpi_ev_gpe_dispatch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff8149030c)
Location: drivers/acpi/acpica/evgpe.c:699
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
```
**Symbols:**

```
ffffffff8149030c-ffffffff8149042e: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff814df0fd)
Location: drivers/acpi/acpica/evgpe.c:699
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
```
**Symbols:**

```
ffffffff814df0fd-ffffffff814df21f: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81501a60)
Location: drivers/acpi/acpica/evgpe.c:754
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
```
**Symbols:**

```
ffffffff81501a60-ffffffff81501b86: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81511f38)
Location: drivers/acpi/acpica/evgpe.c:754
Inline: True
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
```
**Symbols:**

```
ffffffff81511f38-ffffffff8151205e: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81559e95)
Location: drivers/acpi/acpica/evgpe.c:754
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_initialize_gpe_block
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff81559e95-ffffffff8155a03c: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81590995)
Location: drivers/acpi/acpica/evgpe.c:742
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff81590995-ffffffff81590b3c: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815a901d)
Location: drivers/acpi/acpica/evgpe.c:742
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff815a901d-ffffffff815a91d8: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815da7ae)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff815da7ae-ffffffff815da96e: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815fbaee)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff815fbaee-ffffffff815fbcae: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff816a7c11)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff816a7c11-ffffffff816a7dd1: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff816c5407)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff816c5407-ffffffff816c55c7: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff816a7489)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff816a7489-ffffffff816a7649: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff8171e0d0)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff8171e0d0-ffffffff8171e290: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff8184e1a7)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff8184e1a7-ffffffff8184e35f: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff819876a0)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff819876a0-ffffffff81987891: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff819ce0e0)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff819ce0e0-ffffffff819ce2d1: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81a18bb0)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff81a18bb0-ffffffff81a18da1: acpi_ev_gpe_dispatch (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815e5b1e)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
```
**Symbols:**

```
ffffffff815e5b1e-ffffffff815e5c5e: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815d1180)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
```
**Symbols:**

```
ffffffff815d1180-ffffffff815d12c0: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815efdce)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff815efdce-ffffffff815eff8e: acpi_ev_gpe_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 acpi_ev_gpe_dispatch(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81609c7e)
Location: drivers/acpi/acpica/evgpe.c:748
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_generate_gpe
```
**Symbols:**

```
ffffffff81609c7e-ffffffff81609e3e: acpi_ev_gpe_dispatch (STB_GLOBAL)
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
