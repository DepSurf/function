# Function: <code>printk_get_next_message</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool printk_get_next_message(struct printk_message *pmsg, u64 seq, bool is_extended, bool may_suppress);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2757
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_emit_next_record
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff811a0f40-ffffffff811a1258: printk_get_next_message (STB_LOCAL)
ffffffff820d7255-ffffffff820d72a0: printk_get_next_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool printk_get_next_message(struct printk_message *pmsg, u64 seq, bool is_extended, bool may_suppress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2776
Inline: False
Direct callers:
  - kernel/printk/printk.c:console_emit_next_record
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
  - kernel/printk/printk.c:devkmsg_read
```
**Symbols:**

```
ffffffff821b25bf-ffffffff821b260a: printk_get_next_message.cold (STB_LOCAL)
ffffffff811b1660-ffffffff811b1978: printk_get_next_message (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
