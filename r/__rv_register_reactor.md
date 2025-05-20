# Function: <code>__rv_register_reactor</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __rv_register_reactor(struct rv_reactor *reactor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/rv/rv_reactors.c (ffffffff812bdc00)
Location: kernel/trace/rv/rv_reactors.c:278
Inline: True
Direct callers:
  - kernel/trace/rv/rv_reactors.c:init_rv_reactors
  - kernel/trace/rv/rv_reactors.c:rv_register_reactor
```
**Symbols:**

```
ffffffff812bdc00-ffffffff812bdcc6: __rv_register_reactor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __rv_register_reactor(struct rv_reactor *reactor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/rv/rv_reactors.c (ffffffff812e47c0)
Location: kernel/trace/rv/rv_reactors.c:278
Inline: True
Direct callers:
  - kernel/trace/rv/rv_reactors.c:init_rv_reactors
  - kernel/trace/rv/rv_reactors.c:rv_register_reactor
```
**Symbols:**

```
ffffffff812e47c0-ffffffff812e4886: __rv_register_reactor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __rv_register_reactor(struct rv_reactor *reactor);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/rv/rv_reactors.c (ffffffff81302840)
Location: kernel/trace/rv/rv_reactors.c:278
Inline: True
Direct callers:
  - kernel/trace/rv/rv_reactors.c:init_rv_reactors
  - kernel/trace/rv/rv_reactors.c:rv_register_reactor
```
**Symbols:**

```
ffffffff81302840-ffffffff81302935: __rv_register_reactor (STB_LOCAL)
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
