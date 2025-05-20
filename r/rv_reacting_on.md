# Function: <code>rv_reacting_on</code>

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
bool rv_reacting_on();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv_reactors.c (ffffffff812bdce5)
Location: kernel/trace/rv/rv_reactors.c:367
Inline: True
Inline callers:
  - kernel/trace/rv/rv_reactors.c:reacting_on_read_data
Direct callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
```
**Symbols:**

```
ffffffff8205f690-ffffffff8205f6ba: rv_reacting_on.cold (STB_LOCAL)
ffffffff812bdf00-ffffffff812bdf22: rv_reacting_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool rv_reacting_on();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv_reactors.c (ffffffff812e48a5)
Location: kernel/trace/rv/rv_reactors.c:367
Inline: True
Inline callers:
  - kernel/trace/rv/rv_reactors.c:reacting_on_read_data
Direct callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
```
**Symbols:**

```
ffffffff820de5b7-ffffffff820de5e1: rv_reacting_on.cold (STB_LOCAL)
ffffffff812e4ac0-ffffffff812e4ae2: rv_reacting_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool rv_reacting_on();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv_reactors.c (ffffffff81302955)
Location: kernel/trace/rv/rv_reactors.c:367
Inline: True
Inline callers:
  - kernel/trace/rv/rv_reactors.c:reacting_on_read_data
Direct callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:da_event_wwnr
```
**Symbols:**

```
ffffffff821ba435-ffffffff821ba45f: rv_reacting_on.cold (STB_LOCAL)
ffffffff81302b70-ffffffff81302b92: rv_reacting_on (STB_GLOBAL)
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
