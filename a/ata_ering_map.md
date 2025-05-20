# Function: <code>ata_ering_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff815d5375)
Location: drivers/ata/libata-eh.c:403
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_ering_clear
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff815d57c0-ffffffff815d581f: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8162fac1)
Location: drivers/ata/libata-eh.c:403
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff8162f220-ffffffff8162f27e: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81660c11)
Location: drivers/ata/libata-eh.c:403
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff81660370-ffffffff816603ce: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81675c09)
Location: drivers/ata/libata-eh.c:403
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff81675510-ffffffff8167556e: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816df275)
Location: drivers/ata/libata-eh.c:403
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff816deb70-ffffffff816debd0: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8171ba75)
Location: drivers/ata/libata-eh.c:403
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff8171b380-ffffffff8171b3e0: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8173e345)
Location: drivers/ata/libata-eh.c:403
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff8173dc90-ffffffff8173dcf0: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81779eb5)
Location: drivers/ata/libata-eh.c:386
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff817797e0-ffffffff81779840: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179dd51)
Location: drivers/ata/libata-eh.c:386
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff8179d650-ffffffff8179d6b0: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81861605)
Location: drivers/ata/libata-eh.c:385
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down_verdict
  - drivers/ata/libata-eh.c:ata_eh_speed_down_verdict
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff81862310-ffffffff81862370: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81870429)
Location: drivers/ata/libata-eh.c:385
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down_verdict
  - drivers/ata/libata-eh.c:ata_eh_speed_down_verdict
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff81871120-ffffffff81871180: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81852c39)
Location: drivers/ata/libata-eh.c:385
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff81853810-ffffffff81853870: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e0bb9)
Location: drivers/ata/libata-eh.c:393
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff818e1a00-ffffffff818e1a60: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81a3196f)
Location: drivers/ata/libata-eh.c:393
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff81a329a0-ffffffff81a32a0b: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb5dcf)
Location: drivers/ata/libata-eh.c:395
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff81bb70b0-ffffffff81bb711b: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0d300)
Location: drivers/ata/libata-eh.c:395
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff81c0e6a0-ffffffff81c0e726: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c62350)
Location: drivers/ata/libata-eh.c:397
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_handle_port_resume
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_eh_unload
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff81c638b0-ffffffff81c63936: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109a9310)
Location: drivers/ata/libata-eh.c:386
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffff8000109a8958-ffff8000109a89e4: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a78f1c)
Location: drivers/ata/libata-eh.c:386
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
c0a78690-c0a7870c: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a6fc6c)
Location: drivers/ata/libata-eh.c:386
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
c000000000a6f150-c000000000a6f220: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe000607332)
Location: drivers/ata/libata-eh.c:386
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffe000606bb8-ffffffe000606c20: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81762e41)
Location: drivers/ata/libata-eh.c:386
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff81762740-ffffffff817627a0: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81742ca1)
Location: drivers/ata/libata-eh.c:386
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff817425a0-ffffffff81742600: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81792bd1)
Location: drivers/ata/libata-eh.c:386
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff817924d0-ffffffff81792530: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ata_ering_map(struct ata_ering *ering, int (*map_fn)(struct ata_ering_entry *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817aca11)
Location: drivers/ata/libata-eh.c:386
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_ering_clear
Direct callers:
  - drivers/ata/libata-transport.c:show_ata_dev_ering
```
**Symbols:**

```
ffffffff817ac310-ffffffff817ac370: ata_ering_map (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
