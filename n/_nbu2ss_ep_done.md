# Function: <code>_nbu2ss_ep_done</code>

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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void _nbu2ss_ep_done(struct nbu2ss_ep *ep, struct nbu2ss_req *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5c9f8)
Location: drivers/staging/emxx_udc/emxx_udc.c:1825
Inline: False
Direct callers:
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_dequeue
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_ep_queue
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_nuke
```
**Symbols:**

```
c0c5c9f8-c0c5cb00: _nbu2ss_ep_done (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
