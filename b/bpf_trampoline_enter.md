# Function: <code>bpf_trampoline_enter</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bpf_trampoline_enter_t bpf_trampoline_enter(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/trampoline.c (0)
Location: kernel/bpf/trampoline.c:1027
Inline: False
```
**Symbols:**

```
ffffffff82061790-ffffffff820617a5: bpf_trampoline_enter.cold (STB_LOCAL)
ffffffff81308c10-ffffffff81308cbb: bpf_trampoline_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bpf_trampoline_enter_t bpf_trampoline_enter(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/trampoline.c (0)
Location: kernel/bpf/trampoline.c:1005
Inline: False
```
**Symbols:**

```
ffffffff820e0e3e-ffffffff820e0e53: bpf_trampoline_enter.cold (STB_LOCAL)
ffffffff81337b30-ffffffff81337bdb: bpf_trampoline_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bpf_trampoline_enter_t bpf_trampoline_enter(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/trampoline.c (0)
Location: kernel/bpf/trampoline.c:1015
Inline: False
```
**Symbols:**

```
ffffffff821bd67f-ffffffff821bd694: bpf_trampoline_enter.cold (STB_LOCAL)
ffffffff8135d970-ffffffff8135da1b: bpf_trampoline_enter (STB_GLOBAL)
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
