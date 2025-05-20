# Function: <code>hid_bpf_populate_hdev</code>

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
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hid_bpf_populate_hdev(struct hid_device *hdev, enum hid_bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hid/bpf/hid_bpf_jmp_table.c (0)
Location: drivers/hid/bpf/hid_bpf_jmp_table.c:162
Inline: False
Direct callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_release_progs
```
**Symbols:**

```
ffffffff81dd65d0-ffffffff81dd67a7: hid_bpf_populate_hdev (STB_LOCAL)
ffffffff8212b509-ffffffff8212b51d: hid_bpf_populate_hdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hid_bpf_populate_hdev(struct hid_device *hdev, enum hid_bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hid/bpf/hid_bpf_jmp_table.c (0)
Location: drivers/hid/bpf/hid_bpf_jmp_table.c:162
Inline: False
Direct callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_release_progs
```
**Symbols:**

```
ffffffff81e8e7e0-ffffffff81e8e9e5: hid_bpf_populate_hdev (STB_LOCAL)
ffffffff8220d206-ffffffff8220d21a: hid_bpf_populate_hdev.cold (STB_LOCAL)
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
