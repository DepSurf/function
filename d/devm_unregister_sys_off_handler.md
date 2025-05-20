# Function: <code>devm_unregister_sys_off_handler</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_sys_off_handler(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81102b75)
Location: kernel/reboot.c:466
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
**Symbols:**

```
ffffffff81102810-ffffffff81102826: devm_unregister_sys_off_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_sys_off_handler(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81128085)
Location: kernel/reboot.c:483
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
**Symbols:**

```
ffffffff81127c30-ffffffff81127c46: devm_unregister_sys_off_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_sys_off_handler(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff8113553c)
Location: kernel/reboot.c:483
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
**Symbols:**

```
ffffffff81135080-ffffffff81135096: devm_unregister_sys_off_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devm_unregister_sys_off_handler(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81140590)
Location: kernel/reboot.c:497
Inline: True
Inline callers:
  - kernel/reboot.c:devm_register_restart_handler
  - kernel/reboot.c:devm_register_power_off_handler
```
**Symbols:**

```
ffffffff8113ff80-ffffffff8113ff96: devm_unregister_sys_off_handler (STB_LOCAL)
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
