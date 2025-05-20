# Function: <code>enabled_monitors_next</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *enabled_monitors_next(struct seq_file *m, void *p, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff812bc22d)
Location: kernel/trace/rv/rv.c:412
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:enabled_monitors_start
```
**Symbols:**

```
ffffffff812bbaa0-ffffffff812bbb0f: enabled_monitors_next (STB_LOCAL)
ffffffff8205f39b-ffffffff8205f3b7: enabled_monitors_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *enabled_monitors_next(struct seq_file *m, void *p, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff812e2ecd)
Location: kernel/trace/rv/rv.c:410
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:enabled_monitors_start
```
**Symbols:**

```
ffffffff812e2690-ffffffff812e26ff: enabled_monitors_next (STB_LOCAL)
ffffffff820de2e1-ffffffff820de2fd: enabled_monitors_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *enabled_monitors_next(struct seq_file *m, void *p, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff81300f1d)
Location: kernel/trace/rv/rv.c:410
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:enabled_monitors_start
```
**Symbols:**

```
ffffffff813006e0-ffffffff8130074f: enabled_monitors_next (STB_LOCAL)
ffffffff821ba15f-ffffffff821ba17b: enabled_monitors_next.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
