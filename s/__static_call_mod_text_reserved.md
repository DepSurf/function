# Function: <code>__static_call_mod_text_reserved</code>

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
int __static_call_mod_text_reserved(void *start, void *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff81239a20)
Location: kernel/static_call.c:310
Inline: False
Direct callers:
  - kernel/static_call.c:static_call_text_reserved
```
**Symbols:**

```
ffffffff81239a20-ffffffff81239ac9: __static_call_mod_text_reserved (STB_LOCAL)
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
In kernel/static_call.c (ffffffff8123e622)
Location: kernel/static_call.c:312
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_text_reserved
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
In kernel/static_call.c (ffffffff81279102)
Location: kernel/static_call.c:312
Inline: True
Inline callers:
  - kernel/static_call.c:static_call_text_reserved
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
In kernel/static_call_inline.c (ffffffff812cbf98)
Location: kernel/static_call_inline.c:312
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
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
In kernel/static_call_inline.c (ffffffff81333988)
Location: kernel/static_call_inline.c:323
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
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
In kernel/static_call_inline.c (ffffffff813646ae)
Location: kernel/static_call_inline.c:323
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
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
In kernel/static_call_inline.c (ffffffff8138d5de)
Location: kernel/static_call_inline.c:323
Inline: True
Inline callers:
  - kernel/static_call_inline.c:static_call_text_reserved
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
</ul>
