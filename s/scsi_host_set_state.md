# Function: <code>scsi_host_set_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff815a7d90)
Location: drivers/scsi/hosts.c:66
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff815a7d90-ffffffff815a7e78: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff815ffc10)
Location: drivers/scsi/hosts.c:66
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff815ffc10-ffffffff815ffcf8: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8162f270)
Location: drivers/scsi/hosts.c:66
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff8162f270-ffffffff8162f358: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81644050)
Location: drivers/scsi/hosts.c:66
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff81644050-ffffffff8164412e: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816acff0)
Location: drivers/scsi/hosts.c:66
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff816acff0-ffffffff816ad0d4: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816e9c00)
Location: drivers/scsi/hosts.c:72
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff816e9c00-ffffffff816e9cde: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8170d6d0)
Location: drivers/scsi/hosts.c:72
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff8170d6d0-ffffffff8170d7b5: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81748db0)
Location: drivers/scsi/hosts.c:73
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff81748db0-ffffffff81748ea5: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8176cf00)
Location: drivers/scsi/hosts.c:73
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff8176cf00-ffffffff8176cff5: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8182f4c0)
Location: drivers/scsi/hosts.c:74
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff8182f4c0-ffffffff8182f5b5: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff818404f0)
Location: drivers/scsi/hosts.c:74
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_restart_operations
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff818404f0-ffffffff818405e5: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81823730)
Location: drivers/scsi/hosts.c:74
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff81823730-ffffffff81823825: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff818ae060)
Location: drivers/scsi/hosts.c:74
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff818ae060-ffffffff818ae155: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff819f8f10)
Location: drivers/scsi/hosts.c:75
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff819f8f10-ffffffff819f8fff: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81b76af0)
Location: drivers/scsi/hosts.c:75
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff81b76af0-ffffffff81b76bdf: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81bca770)
Location: drivers/scsi/hosts.c:75
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff81bca770-ffffffff81bca858: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81c1f3a0)
Location: drivers/scsi/hosts.c:75
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff81c1f3a0-ffffffff81c1f488: scsi_host_set_state (STB_GLOBAL)
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
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffff80001096f5e8)
Location: drivers/scsi/hosts.c:73
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffff80001096f5e8-ffff80001096f710: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c0a44938)
Location: drivers/scsi/hosts.c:73
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
c0a44938-c0a44a54: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c000000000a28c30)
Location: drivers/scsi/hosts.c:73
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
c000000000a28c30-c000000000a28d8c: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffe0005d96ec)
Location: drivers/scsi/hosts.c:73
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffe0005d96ec-ffffffe0005d97c4: scsi_host_set_state (STB_GLOBAL)
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
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff817215f0)
Location: drivers/scsi/hosts.c:73
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff817215f0-ffffffff817216e5: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816faa20)
Location: drivers/scsi/hosts.c:73
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff816faa20-ffffffff816fab15: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff817603c0)
Location: drivers/scsi/hosts.c:73
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff817603c0-ffffffff817604b5: scsi_host_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_host_set_state(struct Scsi_Host *shost, enum scsi_host_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8177ba20)
Location: drivers/scsi/hosts.c:73
Inline: False
Direct callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/hosts.c:scsi_remove_host
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_error.c:scsi_schedule_eh
  - drivers/scsi/scsi_sysfs.c:store_shost_state
```
**Symbols:**

```
ffffffff8177ba20-ffffffff8177bb15: scsi_host_set_state (STB_GLOBAL)
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
