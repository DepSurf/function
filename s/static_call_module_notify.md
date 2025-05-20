# Function: <code>static_call_module_notify</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int static_call_module_notify(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff81239e00)
Location: kernel/static_call.c:419
Inline: False
```
**Symbols:**

```
ffffffff81239e00-ffffffff81239eb1: static_call_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int static_call_module_notify(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/static_call.c (0)
Location: kernel/static_call.c:421
Inline: False
```
**Symbols:**

```
ffffffff8123e420-ffffffff8123e5a7: static_call_module_notify (STB_LOCAL)
ffffffff81bd8415-ffffffff81bd8432: static_call_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int static_call_module_notify(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/static_call.c (0)
Location: kernel/static_call.c:421
Inline: False
```
**Symbols:**

```
ffffffff81278f00-ffffffff81279087: static_call_module_notify (STB_LOCAL)
ffffffff81cb98a9-ffffffff81cb98c6: static_call_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int static_call_module_notify(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/static_call_inline.c (0)
Location: kernel/static_call_inline.c:421
Inline: False
```
**Symbols:**

```
ffffffff812cbd70-ffffffff812cbf17: static_call_module_notify (STB_LOCAL)
ffffffff81e6ae82-ffffffff81e6aea0: static_call_module_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int static_call_module_notify(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff81333720)
Location: kernel/static_call_inline.c:432
Inline: False
```
**Symbols:**

```
ffffffff81333720-ffffffff813338b8: static_call_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int static_call_module_notify(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff81364470)
Location: kernel/static_call_inline.c:432
Inline: False
```
**Symbols:**

```
ffffffff81364470-ffffffff8136460a: static_call_module_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int static_call_module_notify(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff8138d3a0)
Location: kernel/static_call_inline.c:432
Inline: False
```
**Symbols:**

```
ffffffff8138d3a0-ffffffff8138d53a: static_call_module_notify (STB_LOCAL)
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
