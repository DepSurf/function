# Function: <code>perf_event_ctx_lock_nested</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8117b330)
Location: kernel/events/core.c:957
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_disable
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff8117b330-ffffffff8117b3af: perf_event_ctx_lock_nested.isra.61 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8118cc00)
Location: kernel/events/core.c:1202
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8118cc00-ffffffff8118cc7f: perf_event_ctx_lock_nested.isra.72 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8119c240)
Location: kernel/events/core.c:1210
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8119c240-ffffffff8119c2bf: perf_event_ctx_lock_nested.isra.75 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811a3b50)
Location: kernel/events/core.c:1202
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811a3b50-ffffffff811a3bc3: perf_event_ctx_lock_nested.isra.67 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811b7d20)
Location: kernel/events/core.c:1245
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811b7d20-ffffffff811b7d93: perf_event_ctx_lock_nested.isra.70 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811d7760)
Location: kernel/events/core.c:1268
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811d7760-ffffffff811d77d7: perf_event_ctx_lock_nested.isra.78 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811e8040)
Location: kernel/events/core.c:1268
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811e8040-ffffffff811e80b7: perf_event_ctx_lock_nested.isra.83 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81201ff0)
Location: kernel/events/core.c:1270
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81201ff0-ffffffff81202066: perf_event_ctx_lock_nested.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8120eea0)
Location: kernel/events/core.c:1270
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8120eea0-ffffffff8120ef16: perf_event_ctx_lock_nested.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff812345a0)
Location: kernel/events/core.c:1332
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff812345a0-ffffffff8123461b: perf_event_ctx_lock_nested.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8123eee0)
Location: kernel/events/core.c:1350
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8123eee0-ffffffff8123ef65: perf_event_ctx_lock_nested.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81243050)
Location: kernel/events/core.c:1348
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81243050-ffffffff812430d1: perf_event_ctx_lock_nested.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8127d8a0)
Location: kernel/events/core.c:1379
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8127d8a0-ffffffff8127d921: perf_event_ctx_lock_nested.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff812d1ee0)
Location: kernel/events/core.c:1288
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff812d1ee0-ffffffff812d1f79: perf_event_ctx_lock_nested.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8133acf0)
Location: kernel/events/core.c:1261
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8133acf0-ffffffff8133ad89: perf_event_ctx_lock_nested.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8136bbd0)
Location: kernel/events/core.c:1261
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff8136bbd0-ffffffff8136bc65: perf_event_ctx_lock_nested.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81394d90)
Location: kernel/events/core.c:1272
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_compat_ioctl
  - kernel/events/core.c:perf_event_period
  - kernel/events/core.c:perf_event_pause
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81394d90-ffffffff81394e25: perf_event_ctx_lock_nested.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffff800010293e08)
Location: kernel/events/core.c:1270
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffff800010293e08-ffff800010293e88: perf_event_ctx_lock_nested.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (c04c4dac)
Location: kernel/events/core.c:1270
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
c04c4dac-c04c4e08: perf_event_ctx_lock_nested.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (c000000000343980)
Location: kernel/events/core.c:1270
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
c000000000343980-c000000000343a74: perf_event_ctx_lock_nested.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffe0001c4f6e)
Location: kernel/events/core.c:1270
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffe0001c4f6e-ffffffe0001c4fea: perf_event_ctx_lock_nested.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff812074c0)
Location: kernel/events/core.c:1270
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff812074c0-ffffffff81207536: perf_event_ctx_lock_nested.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811fa360)
Location: kernel/events/core.c:1270
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff811fa360-ffffffff811fa3d6: perf_event_ctx_lock_nested.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81205290)
Location: kernel/events/core.c:1270
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff81205290-ffffffff81205306: perf_event_ctx_lock_nested.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff812140f0)
Location: kernel/events/core.c:1270
Inline: True
Direct callers:
  - kernel/events/core.c:perf_try_init_event
  - kernel/events/core.c:perf_event_task_disable
  - kernel/events/core.c:perf_event_task_enable
  - kernel/events/core.c:perf_ioctl
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:perf_event_refresh
  - kernel/events/core.c:perf_event_enable
  - kernel/events/core.c:perf_event_disable
```
**Symbols:**

```
ffffffff812140f0-ffffffff81214175: perf_event_ctx_lock_nested.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
