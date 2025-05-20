# Function: <code>acpi_ev_walk_gpe_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81490e03)
Location: drivers/acpi/acpica/evgpeutil.c:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff81490e03-ffffffff81490e88: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff814dfbca)
Location: drivers/acpi/acpica/evgpeutil.c:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff814dfbca-ffffffff814dfc4f: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81502530)
Location: drivers/acpi/acpica/evgpeutil.c:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff81502530-ffffffff815025b5: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81512a7c)
Location: drivers/acpi/acpica/evgpeutil.c:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff81512a7c-ffffffff81512b01: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8155b0d1)
Location: drivers/acpi/acpica/evgpeutil.c:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff8155b0d1-ffffffff8155b197: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81591c4e)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff81591c4e-ffffffff81591d14: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815aa2ed)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff815aa2ed-ffffffff815aa3b3: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815dbabb)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff815dbabb-ffffffff815dbb88: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815fcdfe)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff815fcdfe-ffffffff815fcecb: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff816a8fad)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff816a8fad-ffffffff816a907a: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff816c6831)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff816c6831-ffffffff816c68fe: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff816a8865)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff816a8865-ffffffff816a8932: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8171f4ac)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff8171f4ac-ffffffff8171f579: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8184f61e)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff8184f61e-ffffffff8184f6f3: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81988f30)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff81988f30-ffffffff8198901d: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff819cf970)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff819cf970-ffffffff819cfa5d: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81a1a470)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff81a1a470-ffffffff81a1a55d: acpi_ev_walk_gpe_list (STB_GLOBAL)
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
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815e6703)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff815e6703-ffffffff815e678a: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815d1d60)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff815d1d60-ffffffff815d1de7: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff815f10de)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff815f10de-ffffffff815f11ab: acpi_ev_walk_gpe_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ev_walk_gpe_list(acpi_gpe_callback gpe_walk_callback, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evgpeutil.c (ffffffff8160af8e)
Location: drivers/acpi/acpica/evgpeutil.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evmisc.c:acpi_ev_terminate
  - drivers/acpi/acpica/evxfgpe.c:acpi_get_gpe_device
  - drivers/acpi/acpica/evxfgpe.c:acpi_update_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_check_all_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_wakeup_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_enable_all_runtime_gpes
  - drivers/acpi/acpica/hwgpe.c:acpi_hw_disable_all_gpes
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
```
**Symbols:**

```
ffffffff8160af8e-ffffffff8160b05b: acpi_ev_walk_gpe_list (STB_GLOBAL)
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
