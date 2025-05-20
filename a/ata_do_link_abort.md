# Function: <code>ata_do_link_abort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff815d4e40)
Location: drivers/ata/libata-eh.c:1048
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_link_abort
  - drivers/ata/libata-eh.c:ata_port_freeze
```
**Symbols:**

```
ffffffff815d4e40-ffffffff815d4f1e: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8162e8c0)
Location: drivers/ata/libata-eh.c:1048
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff8162e8c0-ffffffff8162e99e: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8165fa10)
Location: drivers/ata/libata-eh.c:1048
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff8165fa10-ffffffff8165faee: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81674460)
Location: drivers/ata/libata-eh.c:1049
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff81674460-ffffffff81674535: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816ddac0)
Location: drivers/ata/libata-eh.c:1047
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff816ddac0-ffffffff816ddb9b: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8171a2d0)
Location: drivers/ata/libata-eh.c:998
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff8171a2d0-ffffffff8171a3ac: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8173cbd0)
Location: drivers/ata/libata-eh.c:994
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff8173cbd0-ffffffff8173ccac: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff81778710-ffffffff817787e4: ata_do_link_abort (STB_LOCAL)
ffffffff8177de51-ffffffff8177de64: ata_do_link_abort.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179c580)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff8179c580-ffffffff8179c65b: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81861180)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_unload
```
**Symbols:**

```
ffffffff81861180-ffffffff81861255: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8186ffa0)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_unload
```
**Symbols:**

```
ffffffff8186ffa0-ffffffff81870075: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818527b0)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff818527b0-ffffffff81852885: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e05f0)
Location: drivers/ata/libata-eh.c:985
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff818e05f0-ffffffff818e06d6: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81a312f0)
Location: drivers/ata/libata-eh.c:982
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff81a312f0-ffffffff81a313de: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb56e0)
Location: drivers/ata/libata-eh.c:984
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff81bb56e0-ffffffff81bb57ce: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0cc30)
Location: drivers/ata/libata-eh.c:987
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
**Symbols:**

```
ffffffff81c0cc30-ffffffff81c0cd1e: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c60790)
Location: drivers/ata/libata-eh.c:1005
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_link_abort
  - drivers/ata/libata-eh.c:ata_eh_fastdrain_timerfn
  - drivers/ata/libata-eh.c:ata_eh_unload
```
**Symbols:**

```
ffffffff81c60790-ffffffff81c60868: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109a7200)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffff8000109a7200-ffff8000109a72e8: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a77378)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
c0a77378-c0a77478: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a6d850)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
c000000000a6d850-c000000000a6d9b8: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe000605a6e)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffe000605a6e-ffffffe000605b2e: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81761670)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff81761670-ffffffff8176174b: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817414d0)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff817414d0-ffffffff817415ab: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81791400)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff81791400-ffffffff817914db: ata_do_link_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ata_do_link_abort(struct ata_port *ap, struct ata_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817ab240)
Location: drivers/ata/libata-eh.c:977
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_port_freeze
  - drivers/ata/libata-eh.c:ata_link_abort
```
**Symbols:**

```
ffffffff817ab240-ffffffff817ab31b: ata_do_link_abort (STB_LOCAL)
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
