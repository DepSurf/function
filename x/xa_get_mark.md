# Function: <code>xa_get_mark</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17de0)
Location: lib/xarray.c:1702
Inline: False
```
**Symbols:**

```
ffffffff81a17de0-ffffffff81a17eb8: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a879a0)
Location: lib/xarray.c:1729
Inline: False
```
**Symbols:**

```
ffffffff81a879a0-ffffffff81a87a7f: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abec40)
Location: lib/xarray.c:1740
Inline: False
```
**Symbols:**

```
ffffffff81abec40-ffffffff81abed1f: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fb180)
Location: lib/xarray.c:1742
Inline: False
```
**Symbols:**

```
ffffffff815fb180-ffffffff815fb29f: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161fce0)
Location: lib/xarray.c:1932
Inline: False
```
**Symbols:**

```
ffffffff8161fce0-ffffffff8161fe0b: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81603460)
Location: lib/xarray.c:1933
Inline: False
```
**Symbols:**

```
ffffffff81603460-ffffffff8160358b: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1933
Inline: False
```
**Symbols:**

```
ffffffff81ce0038-ffffffff81ce009b: xa_get_mark.cold (STB_LOCAL)
ffffffff81671df0-ffffffff81671f90: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1940
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_unregister
  - net/core/devlink.c:devlink_param_register
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:devlink_params_register
  - net/core/devlink.c:devlink_free
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_set_features
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_param_notify
  - net/core/devlink.c:devlink_linecard_notify
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff81ea67a2-ffffffff81ea67d6: xa_get_mark.cold (STB_LOCAL)
ffffffff8178c580-ffffffff8178c73a: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1940
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_param_driverinit_value_set
  - net/core/devlink.c:devlink_param_unregister
  - net/core/devlink.c:devlink_param_register
  - net/core/devlink.c:devlink_params_unregister
  - net/core/devlink.c:devlink_params_register
  - net/core/devlink.c:devlink_free
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_register
  - net/core/devlink.c:devlink_set_features
  - net/core/devlink.c:devlink_nl_region_notify
  - net/core/devlink.c:devlink_linecard_notify
  - net/core/devlink.c:devlink_rate_notify
  - net/core/devlink.c:devlink_port_notify
  - net/core/devlink.c:devlink_notify
```
**Symbols:**

```
ffffffff820b8028-ffffffff820b805c: xa_get_mark.cold (STB_LOCAL)
ffffffff82049c20-ffffffff82049dda: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1938
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_region_notify
  - net/devlink/leftover.c:devlink_linecard_notify
  - net/devlink/leftover.c:devlink_rate_notify
  - net/devlink/leftover.c:devlink_port_notify
  - net/devlink/core.c:devlink_pernet_pre_exit
  - net/devlink/core.c:devlink_free
  - net/devlink/core.c:devlink_unregister
  - net/devlink/core.c:devl_unregister
  - net/devlink/core.c:devlink_register
  - net/devlink/core.c:devl_register
  - net/devlink/netlink.c:devlink_nl_instance_iter_dumpit
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_compat_running_version
  - net/devlink/dev.c:devlink_notify
```
**Symbols:**

```
ffffffff8213939a-ffffffff821393b3: xa_get_mark.cold (STB_LOCAL)
ffffffff820c7d40-ffffffff820c7e92: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1944
Inline: False
Direct callers:
  - drivers/dpll/dpll_core.c:dpll_device_unregister
  - drivers/dpll/dpll_core.c:dpll_device_put
  - drivers/dpll/dpll_core.c:dpll_device_get_by_id
  - drivers/dpll/dpll_netlink.c:dpll_pin_available
  - drivers/dpll/dpll_netlink.c:dpll_pin_available
  - drivers/dpll/dpll_netlink.c:dpll_pin_available
  - drivers/dpll/dpll_netlink.c:dpll_device_event_send
  - net/devlink/core.c:devlink_pernet_pre_exit
  - net/devlink/core.c:devlink_free
  - net/devlink/core.c:devl_unregister
  - net/devlink/core.c:devl_register
  - net/devlink/core.c:devlink_rel_nested_in_add
  - net/devlink/core.c:devlink_rel_nested_in_add
  - net/devlink/core.c:devlink_rel_nested_in_notify_work
  - net/devlink/core.c:devlink_rel_nested_in_notify_work
  - net/devlink/netlink.c:devlink_nl_dumpit
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
  - net/devlink/netlink.c:devlink_get_from_attrs_lock
  - net/devlink/dev.c:devlink_compat_flash_update
  - net/devlink/dev.c:devlink_compat_running_version
  - net/devlink/port.c:devlink_port_notify
  - net/devlink/region.c:devlink_nl_region_notify
  - net/devlink/rate.c:devlink_rate_notify
  - net/devlink/linecard.c:devlink_linecard_notify
```
**Symbols:**

```
ffffffff8221b13f-ffffffff8221b158: xa_get_mark.cold (STB_LOCAL)
ffffffff821a26c0-ffffffff821a2812: xa_get_mark (STB_GLOBAL)
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
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d99c58)
Location: lib/xarray.c:1740
Inline: False
```
**Symbols:**

```
ffff800010d99c58-ffff800010d99d2c: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e967a0)
Location: lib/xarray.c:1740
Inline: False
```
**Symbols:**

```
c0e967a0-c0e96874: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000edfc90)
Location: lib/xarray.c:1740
Inline: False
```
**Symbols:**

```
c000000000edfc90-c000000000edfdac: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c2880)
Location: lib/xarray.c:1740
Inline: False
```
**Symbols:**

```
ffffffe0008c2880-ffffffe0008c2916: xa_get_mark (STB_GLOBAL)
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
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5da90)
Location: lib/xarray.c:1740
Inline: False
```
**Symbols:**

```
ffffffff81a5da90-ffffffff81a5db6f: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1ab60)
Location: lib/xarray.c:1740
Inline: False
```
**Symbols:**

```
ffffffff81a1ab60-ffffffff81a1ac3f: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac9e80)
Location: lib/xarray.c:1740
Inline: False
```
**Symbols:**

```
ffffffff81ac9e80-ffffffff81ac9f5f: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool xa_get_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad63f0)
Location: lib/xarray.c:1740
Inline: False
```
**Symbols:**

```
ffffffff81ad63f0-ffffffff81ad64e3: xa_get_mark (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
