# Function: <code>sigaltstack_size_valid</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool sigaltstack_size_valid(size_t ss_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:948
Inline: False
```
**Symbols:**

```
ffffffff81e4776b-ffffffff81e47794: sigaltstack_size_valid.cold (STB_LOCAL)
ffffffff810424e0-ffffffff8104258d: sigaltstack_size_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool sigaltstack_size_valid(size_t ss_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:385
Inline: False
```
**Symbols:**

```
ffffffff82051f87-ffffffff82051fb0: sigaltstack_size_valid.cold (STB_LOCAL)
ffffffff8104b7d0-ffffffff8104b87d: sigaltstack_size_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool sigaltstack_size_valid(size_t ss_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:387
Inline: False
```
**Symbols:**

```
ffffffff820d04b2-ffffffff820d04db: sigaltstack_size_valid.cold (STB_LOCAL)
ffffffff8104c060-ffffffff8104c10d: sigaltstack_size_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool sigaltstack_size_valid(size_t ss_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:389
Inline: False
```
**Symbols:**

```
ffffffff821aafc7-ffffffff821aaff0: sigaltstack_size_valid.cold (STB_LOCAL)
ffffffff810532e0-ffffffff8105338d: sigaltstack_size_valid (STB_GLOBAL)
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
