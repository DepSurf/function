# Function: <code>rv_unregister_reactor</code>

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
int rv_unregister_reactor(struct rv_reactor *reactor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rv/rv_reactors.c (ffffffff812bde10)
Location: kernel/trace/rv/rv_reactors.c:329
Inline: False
Direct callers:
  - kernel/trace/rv/reactor_printk.c:unregister_react_printk
  - kernel/trace/rv/reactor_panic.c:unregister_react_panic
```
**Symbols:**

```
ffffffff812bde10-ffffffff812bdeee: rv_unregister_reactor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rv_unregister_reactor(struct rv_reactor *reactor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rv/rv_reactors.c (ffffffff812e49d0)
Location: kernel/trace/rv/rv_reactors.c:329
Inline: False
Direct callers:
  - kernel/trace/rv/reactor_printk.c:unregister_react_printk
  - kernel/trace/rv/reactor_panic.c:unregister_react_panic
```
**Symbols:**

```
ffffffff812e49d0-ffffffff812e4aae: rv_unregister_reactor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rv_unregister_reactor(struct rv_reactor *reactor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rv/rv_reactors.c (ffffffff81302a80)
Location: kernel/trace/rv/rv_reactors.c:329
Inline: False
Direct callers:
  - kernel/trace/rv/reactor_printk.c:unregister_react_printk
  - kernel/trace/rv/reactor_panic.c:unregister_react_panic
```
**Symbols:**

```
ffffffff81302a80-ffffffff81302b5e: rv_unregister_reactor (STB_GLOBAL)
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
