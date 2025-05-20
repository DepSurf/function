# Function: <code>__hid_bpf_allocate_data</code>

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
int __hid_bpf_allocate_data(struct hid_device *hdev, u8 **data, u32 *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hid/bpf/hid_bpf_dispatch.c (ffffffff81dd58b0)
Location: drivers/hid/bpf/hid_bpf_dispatch.c:191
Inline: False
Direct callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_connect_device
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
```
**Symbols:**

```
ffffffff81dd58b0-ffffffff81dd5987: __hid_bpf_allocate_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __hid_bpf_allocate_data(struct hid_device *hdev, u8 **data, u32 *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hid/bpf/hid_bpf_dispatch.c (ffffffff81e8da00)
Location: drivers/hid/bpf/hid_bpf_dispatch.c:195
Inline: False
Direct callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_connect_device
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog
```
**Symbols:**

```
ffffffff81e8da00-ffffffff81e8dad7: __hid_bpf_allocate_data (STB_LOCAL)
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
