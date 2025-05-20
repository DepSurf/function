# Function: <code>static_call_del_module</code>

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
void static_call_del_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff81239790)
Location: kernel/static_call.c:390
Inline: False
Direct callers:
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:static_call_module_notify
```
**Symbols:**

```
ffffffff81239790-ffffffff81239812: static_call_del_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void static_call_del_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff8123df80)
Location: kernel/static_call.c:392
Inline: False
Direct callers:
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:static_call_module_notify
```
**Symbols:**

```
ffffffff8123df80-ffffffff8123e002: static_call_del_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void static_call_del_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff81278a40)
Location: kernel/static_call.c:392
Inline: False
Direct callers:
  - kernel/static_call.c:static_call_module_notify
  - kernel/static_call.c:static_call_module_notify
```
**Symbols:**

```
ffffffff81278a40-ffffffff81278ac2: static_call_del_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void static_call_del_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff812cb890)
Location: kernel/static_call_inline.c:392
Inline: False
Direct callers:
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:static_call_module_notify
```
**Symbols:**

```
ffffffff812cb890-ffffffff812cb919: static_call_del_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void static_call_del_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff81333210)
Location: kernel/static_call_inline.c:403
Inline: False
Direct callers:
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:static_call_module_notify
```
**Symbols:**

```
ffffffff81333210-ffffffff81333299: static_call_del_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void static_call_del_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff81363ee0)
Location: kernel/static_call_inline.c:403
Inline: False
Direct callers:
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:static_call_module_notify
```
**Symbols:**

```
ffffffff81363ee0-ffffffff81363f69: static_call_del_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void static_call_del_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff8138cdb0)
Location: kernel/static_call_inline.c:403
Inline: False
Direct callers:
  - kernel/static_call_inline.c:static_call_module_notify
  - kernel/static_call_inline.c:static_call_module_notify
```
**Symbols:**

```
ffffffff8138cdb0-ffffffff8138ce39: static_call_del_module (STB_LOCAL)
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
