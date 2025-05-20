# Function: <code>hid_bpf_get_prog_attach_type</code>

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
<summary>In <code>6.5</code>: ✅</summary>

```c
int hid_bpf_get_prog_attach_type(int prog_fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81dd6cc0)
Location: drivers/hid/bpf/hid_bpf_jmp_table.c:336
Inline: False
Direct callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
```
**Symbols:**

```
ffffffff81dd6cc0-ffffffff81dd6d1f: hid_bpf_get_prog_attach_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hid_bpf_get_prog_attach_type(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81e8ef50)
Location: drivers/hid/bpf/hid_bpf_jmp_table.c:350
Inline: False
Direct callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
```
**Symbols:**

```
ffffffff81e8ef50-ffffffff81e8ef8a: hid_bpf_get_prog_attach_type (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog *prog</code>
</li>
<li>
<b>Param removed. </b>
<code>int prog_fd</code>
</li>
</ul>
</details>
</li>
</ul>
