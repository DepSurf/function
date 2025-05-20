# Function: <code>acpi_ev_detect_gpe</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81590b3c)
Location: drivers/acpi/acpica/evgpe.c:620
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff81590b3c-ffffffff81590d0c: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815a91d8)
Location: drivers/acpi/acpica/evgpe.c:620
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815a91d8-ffffffff815a93b7: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815da96e)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815da96e-ffffffff815dab4b: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815fbcae)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815fbcae-ffffffff815fbe8b: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff816a7dd1)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff816a7dd1-ffffffff816a7fb3: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff816c55c7)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff816c55c7-ffffffff816c57a9: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff816a7649)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff816a7649-ffffffff816a782b: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff8171e290)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff8171e290-ffffffff8171e472: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff8184e35f)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff8184e35f-ffffffff8184e543: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff819878b0)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff819878b0-ffffffff81987aac: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff819ce2f0)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff819ce2f0-ffffffff819ce4ec: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81a18dc0)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxface.c:acpi_remove_gpe_handler
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff81a18dc0-ffffffff81a18fbc: acpi_ev_detect_gpe (STB_GLOBAL)
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
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815e5c5e)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815e5c5e-ffffffff815e5dc0: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815d12c0)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815d12c0-ffffffff815d1422: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff815eff8e)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff815eff8e-ffffffff815f016b: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 acpi_ev_detect_gpe(struct acpi_namespace_node *gpe_device, struct acpi_gpe_event_info *gpe_event_info, u32 gpe_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpe.c (ffffffff81609e3e)
Location: drivers/acpi/acpica/evgpe.c:626
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_detect
  - drivers/acpi/acpica/evxfgpe.c:acpi_dispatch_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_enable_gpe
```
**Symbols:**

```
ffffffff81609e3e-ffffffff8160a01b: acpi_ev_detect_gpe (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
