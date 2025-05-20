# Function: <code>get_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117a060)
Location: kernel/events/core.c:870
Inline: True
Direct callers:
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_init_task
```
**Symbols:**

```
ffffffff8117a060-ffffffff8117a0b2: get_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118ade0)
Location: kernel/events/core.c:1115
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff8118ade0-ffffffff8118ae31: get_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81199e20)
Location: kernel/events/core.c:1123
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff81199e20-ffffffff81199e71: get_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1c20)
Location: kernel/events/core.c:1115
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811a1c20-ffffffff811a1c57: get_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b5830)
Location: kernel/events/core.c:1154
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:SYSC_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811b5830-ffffffff811b5867: get_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d46c0)
Location: kernel/events/core.c:1177
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811d46c0-ffffffff811d46f7: get_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e5080)
Location: kernel/events/core.c:1177
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811e5080-ffffffff811e50b7: get_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f9d90)
Location: kernel/events/core.c:1178
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811f9d90-ffffffff811f9d9e: get_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81206e60)
Location: kernel/events/core.c:1178
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff81206e60-ffffffff81206e6e: get_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123e15c)
Location: kernel/events/core.c:1240
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124851c)
Location: kernel/events/core.c:1244
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
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
In kernel/events/core.c (ffffffff8124c426)
Location: kernel/events/core.c:1242
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
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
In kernel/events/core.c (ffffffff81287d2c)
Location: kernel/events/core.c:1273
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
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
In kernel/events/core.c (ffffffff812dc54b)
Location: kernel/events/core.c:1182
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81344806)
Location: kernel/events/core.c:1156
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813758a6)
Location: kernel/events/core.c:1156
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139ebd6)
Location: kernel/events/core.c:1167
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:__perf_pmu_install_event
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102a14f0)
Location: kernel/events/core.c:1178
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04d1698)
Location: kernel/events/core.c:1178
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000353844)
Location: kernel/events/core.c:1178
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001d07ec)
Location: kernel/events/core.c:1178
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:find_get_context
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
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ff480)
Location: kernel/events/core.c:1178
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811ff480-ffffffff811ff48e: get_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f21d0)
Location: kernel/events/core.c:1178
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811f21d0-ffffffff811f21de: get_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd250)
Location: kernel/events/core.c:1178
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff811fd250-ffffffff811fd25e: get_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void get_ctx(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120bf20)
Location: kernel/events/core.c:1178
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:perf_pmu_migrate_context
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:perf_event_release_kernel
```
**Symbols:**

```
ffffffff8120bf20-ffffffff8120bf2e: get_ctx (STB_LOCAL)
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
