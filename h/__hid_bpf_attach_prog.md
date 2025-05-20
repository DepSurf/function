# Function: <code>__hid_bpf_attach_prog</code>

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
int __hid_bpf_attach_prog(struct hid_device *hdev, enum hid_bpf_prog_type prog_type, int prog_fd, __u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81dd6d30)
Location: drivers/hid/bpf/hid_bpf_jmp_table.c:390
Inline: False
Direct callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
```
**Symbols:**

```
ffffffff81dd6d30-ffffffff81dd71fe: __hid_bpf_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __hid_bpf_attach_prog(struct hid_device *hdev, enum hid_bpf_prog_type prog_type, int prog_fd, struct bpf_prog *prog, __u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81e8efa0)
Location: drivers/hid/bpf/hid_bpf_jmp_table.c:397
Inline: False
Direct callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
```
**Symbols:**

```
ffffffff81e8efa0-ffffffff81e8f492: __hid_bpf_attach_prog (STB_GLOBAL)
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
<b>Param reordered. </b>
<code>hdev, prog_type, prog_fd, flags</code> ➡️ <code>hdev, prog_type, prog_fd, prog, flags</code>
</li>
</ul>
</details>
</li>
</ul>
