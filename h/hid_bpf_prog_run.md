# Function: <code>hid_bpf_prog_run</code>

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
int hid_bpf_prog_run(struct hid_device *hdev, enum hid_bpf_prog_type type, struct hid_bpf_ctx_kern *ctx_kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81dd6be0)
Location: drivers/hid/bpf/hid_bpf_jmp_table.c:107
Inline: False
Direct callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:call_hid_bpf_rdesc_fixup
  - drivers/hid/bpf/hid_bpf_dispatch.c:dispatch_hid_bpf_device_event
```
**Symbols:**

```
ffffffff81dd6be0-ffffffff81dd6cac: hid_bpf_prog_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hid_bpf_prog_run(struct hid_device *hdev, enum hid_bpf_prog_type type, struct hid_bpf_ctx_kern *ctx_kern);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81e8ee70)
Location: drivers/hid/bpf/hid_bpf_jmp_table.c:107
Inline: False
Direct callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:call_hid_bpf_rdesc_fixup
  - drivers/hid/bpf/hid_bpf_dispatch.c:dispatch_hid_bpf_device_event
```
**Symbols:**

```
ffffffff81e8ee70-ffffffff81e8ef3b: hid_bpf_prog_run (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
