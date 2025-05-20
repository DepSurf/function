# Function: <code>unregister_sys_off_handler</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void unregister_sys_off_handler(struct sys_off_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:445
Inline: False
Direct callers:
  - kernel/reboot.c:do_kernel_power_off
  - kernel/reboot.c:unregister_platform_power_off
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
**Symbols:**

```
ffffffff81e5503e-ffffffff81e55053: unregister_sys_off_handler.cold (STB_LOCAL)
ffffffff81102770-ffffffff8110280a: unregister_sys_off_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void unregister_sys_off_handler(struct sys_off_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:462
Inline: False
Direct callers:
  - kernel/reboot.c:do_kernel_power_off
  - kernel/reboot.c:unregister_platform_power_off
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
**Symbols:**

```
ffffffff82056853-ffffffff82056868: unregister_sys_off_handler.cold (STB_LOCAL)
ffffffff81127b80-ffffffff81127c1a: unregister_sys_off_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void unregister_sys_off_handler(struct sys_off_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:462
Inline: False
Direct callers:
  - kernel/reboot.c:do_kernel_power_off
  - kernel/reboot.c:unregister_platform_power_off
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
**Symbols:**

```
ffffffff820d4ec2-ffffffff820d4ed7: unregister_sys_off_handler.cold (STB_LOCAL)
ffffffff81134fd0-ffffffff8113506a: unregister_sys_off_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void unregister_sys_off_handler(struct sys_off_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:476
Inline: False
Direct callers:
  - kernel/reboot.c:do_kernel_power_off
  - kernel/reboot.c:unregister_platform_power_off
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
**Symbols:**

```
ffffffff821afda9-ffffffff821afdbe: unregister_sys_off_handler.cold (STB_LOCAL)
ffffffff8113fed0-ffffffff8113ff6a: unregister_sys_off_handler (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
