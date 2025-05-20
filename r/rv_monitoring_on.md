# Function: <code>rv_monitoring_on</code>

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
bool rv_monitoring_on();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff812bc3ef)
Location: kernel/trace/rv/rv.c:586
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:monitoring_on_read_data
Direct callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:handle_wakeup
  - kernel/trace/rv/monitors/wwnr/wwnr.c:handle_switch
  - kernel/trace/rv/monitors/wwnr/wwnr.c:handle_switch
  - kernel/trace/rv/monitors/wwnr/wwnr.c:handle_switch
```
**Symbols:**

```
ffffffff8205f51d-ffffffff8205f547: rv_monitoring_on.cold (STB_LOCAL)
ffffffff812bca50-ffffffff812bca72: rv_monitoring_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool rv_monitoring_on();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff812e308f)
Location: kernel/trace/rv/rv.c:584
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:monitoring_on_read_data
Direct callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:handle_wakeup
  - kernel/trace/rv/monitors/wwnr/wwnr.c:handle_switch
  - kernel/trace/rv/monitors/wwnr/wwnr.c:handle_switch
  - kernel/trace/rv/monitors/wwnr/wwnr.c:handle_switch
```
**Symbols:**

```
ffffffff820de44e-ffffffff820de478: rv_monitoring_on.cold (STB_LOCAL)
ffffffff812e3620-ffffffff812e3642: rv_monitoring_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool rv_monitoring_on();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff813010df)
Location: kernel/trace/rv/rv.c:584
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:monitoring_on_read_data
Direct callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:handle_wakeup
  - kernel/trace/rv/monitors/wwnr/wwnr.c:handle_switch
  - kernel/trace/rv/monitors/wwnr/wwnr.c:handle_switch
  - kernel/trace/rv/monitors/wwnr/wwnr.c:handle_switch
```
**Symbols:**

```
ffffffff821ba2cc-ffffffff821ba2f6: rv_monitoring_on.cold (STB_LOCAL)
ffffffff81301670-ffffffff81301692: rv_monitoring_on (STB_GLOBAL)
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
