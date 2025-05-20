# Function: <code>bau_process_message</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bau_process_message(struct msg_desc *mdp, struct bau_control *bcp, int do_acknowledge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/tlb_uv.c (ffffffff810950a0)
Location: arch/x86/platform/uv/tlb_uv.c:282
Inline: False
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
```
**Symbols:**

```
ffffffff810950a0-ffffffff810952b1: bau_process_message (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bau_process_message(struct msg_desc *mdp, struct bau_control *bcp, int do_acknowledge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109a700)
Location: arch/x86/platform/uv/tlb_uv.c:282
Inline: False
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:__sysvec_uv_bau_message
  - arch/x86/platform/uv/tlb_uv.c:__sysvec_uv_bau_message
```
**Symbols:**

```
ffffffff8109a700-ffffffff8109a814: bau_process_message (STB_LOCAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bau_process_message(struct msg_desc *mdp, struct bau_control *bcp, int do_acknowledge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81096560)
Location: arch/x86/platform/uv/tlb_uv.c:282
Inline: False
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_message_interrupt
```
**Symbols:**

```
ffffffff81096560-ffffffff81096771: bau_process_message (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
