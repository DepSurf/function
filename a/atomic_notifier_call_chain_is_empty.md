# Function: <code>atomic_notifier_call_chain_is_empty</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
bool atomic_notifier_call_chain_is_empty(struct atomic_notifier_head *nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81100ba0)
Location: kernel/notifier.c:241
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
```
**Symbols:**

```
ffffffff81100ba0-ffffffff81100bbb: atomic_notifier_call_chain_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool atomic_notifier_call_chain_is_empty(struct atomic_notifier_head *nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81125b40)
Location: kernel/notifier.c:241
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
```
**Symbols:**

```
ffffffff81125b40-ffffffff81125b5b: atomic_notifier_call_chain_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool atomic_notifier_call_chain_is_empty(struct atomic_notifier_head *nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132fb0)
Location: kernel/notifier.c:247
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
```
**Symbols:**

```
ffffffff81132fb0-ffffffff81132fcb: atomic_notifier_call_chain_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool atomic_notifier_call_chain_is_empty(struct atomic_notifier_head *nh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113dec0)
Location: kernel/notifier.c:247
Inline: False
Direct callers:
  - kernel/reboot.c:__do_sys_reboot
```
**Symbols:**

```
ffffffff8113dec0-ffffffff8113dedb: atomic_notifier_call_chain_is_empty (STB_GLOBAL)
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
