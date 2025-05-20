# Function: <code>reactor_cleanup_monitor</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void reactor_cleanup_monitor(struct rv_monitor_def *mdef);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rv/rv_reactors.c (ffffffff812bdff0)
Location: kernel/trace/rv/rv_reactors.c:462
Inline: False
Direct callers:
  - kernel/trace/rv/rv.c:rv_unregister_monitor
```
**Symbols:**

```
ffffffff812bdff0-ffffffff812be022: reactor_cleanup_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reactor_cleanup_monitor(struct rv_monitor_def *mdef);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rv/rv_reactors.c (ffffffff812e4bb0)
Location: kernel/trace/rv/rv_reactors.c:462
Inline: False
Direct callers:
  - kernel/trace/rv/rv.c:rv_unregister_monitor
```
**Symbols:**

```
ffffffff812e4bb0-ffffffff812e4be2: reactor_cleanup_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reactor_cleanup_monitor(struct rv_monitor_def *mdef);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rv/rv_reactors.c (ffffffff81302c60)
Location: kernel/trace/rv/rv_reactors.c:462
Inline: False
Direct callers:
  - kernel/trace/rv/rv.c:rv_unregister_monitor
```
**Symbols:**

```
ffffffff81302c60-ffffffff81302c92: reactor_cleanup_monitor (STB_GLOBAL)
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
