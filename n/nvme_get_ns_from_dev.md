# Function: <code>nvme_get_ns_from_dev</code>

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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff8174215b)
Location: drivers/nvme/host/nvme.h:650
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_ns_id_attrs_are_visible
  - drivers/nvme/host/core.c:nvme_ns_id_attrs_are_visible
  - drivers/nvme/host/core.c:nsid_show
  - drivers/nvme/host/core.c:eui_show
  - drivers/nvme/host/core.c:uuid_show
  - drivers/nvme/host/core.c:nguid_show
  - drivers/nvme/host/core.c:wwid_show
```
```
In drivers/nvme/host/multipath.c (ffffffff817494f5)
Location: drivers/nvme/host/nvme.h:650
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:ana_state_show
  - drivers/nvme/host/multipath.c:ana_grpid_show
```
```
In drivers/nvme/host/lightnvm.c (ffffffff8174b2f5)
Location: drivers/nvme/host/nvme.h:650
Inline: True
Inline callers:
  - drivers/nvme/host/lightnvm.c:nvm_dev_attr_show_20
  - drivers/nvme/host/lightnvm.c:nvm_dev_attr_show_12
  - drivers/nvme/host/lightnvm.c:nvm_dev_attr_show
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81723deb)
Location: drivers/nvme/host/nvme.h:650
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_ns_id_attrs_are_visible
  - drivers/nvme/host/core.c:nvme_ns_id_attrs_are_visible
  - drivers/nvme/host/core.c:nsid_show
  - drivers/nvme/host/core.c:eui_show
  - drivers/nvme/host/core.c:uuid_show
  - drivers/nvme/host/core.c:nguid_show
  - drivers/nvme/host/core.c:wwid_show
```
```
In drivers/nvme/host/multipath.c (ffffffff8172b0e5)
Location: drivers/nvme/host/nvme.h:650
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:ana_state_show
  - drivers/nvme/host/multipath.c:ana_grpid_show
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
