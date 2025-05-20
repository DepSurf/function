# Function: <code>__static_call_init</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/static_call.c (ffffffff81239dcb)
Location: kernel/static_call.c:209
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_add_module
  - kernel/static_call.c:static_call_init
Direct callers:
  - kernel/static_call.c:static_call_add_module
  - kernel/static_call.c:static_call_init
```
**Symbols:**

```
ffffffff81239ad0-ffffffff81239ce1: __static_call_init.part.0 (STB_LOCAL)
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
In kernel/static_call.c (ffffffff8123e549)
Location: kernel/static_call.c:209
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:static_call_init
Direct callers:
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:static_call_init
```
**Symbols:**

```
ffffffff8123e210-ffffffff8123e41b: __static_call_init.part.0 (STB_LOCAL)
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
In kernel/static_call.c (ffffffff81279029)
Location: kernel/static_call.c:209
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:static_call_init
Direct callers:
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:static_call_init
```
**Symbols:**

```
ffffffff81278cf0-ffffffff81278efb: __static_call_init.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __static_call_init(struct module *mod, struct static_call_site *start, struct static_call_site *stop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff812cbb60)
Location: kernel/static_call_inline.c:209
Inline: False
Direct callers:
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:static_call_init
```
**Symbols:**

```
ffffffff812cbb60-ffffffff812cbd6e: __static_call_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __static_call_init(struct module *mod, struct static_call_site *start, struct static_call_site *stop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff81333500)
Location: kernel/static_call_inline.c:220
Inline: False
Direct callers:
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:static_call_init
```
**Symbols:**

```
ffffffff81333500-ffffffff8133370e: __static_call_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __static_call_init(struct module *mod, struct static_call_site *start, struct static_call_site *stop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff813641d0)
Location: kernel/static_call_inline.c:220
Inline: False
Direct callers:
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:static_call_init
```
**Symbols:**

```
ffffffff813641d0-ffffffff8136445f: __static_call_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __static_call_init(struct module *mod, struct static_call_site *start, struct static_call_site *stop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff8138d0a0)
Location: kernel/static_call_inline.c:220
Inline: False
Direct callers:
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:static_call_init
```
**Symbols:**

```
ffffffff8138d0a0-ffffffff8138d381: __static_call_init (STB_LOCAL)
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
