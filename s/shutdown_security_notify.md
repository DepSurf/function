# Function: <code>shutdown_security_notify</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5130)
Location: drivers/nvdimm/dimm_devs.c:581
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff816f5130-ffffffff816f5147: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8172e9e0)
Location: drivers/nvdimm/dimm_devs.c:580
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff8172e9e0-ffffffff8172e9f7: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81752ca0)
Location: drivers/nvdimm/dimm_devs.c:508
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff81752ca0-ffffffff81752cb7: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81811c59)
Location: drivers/nvdimm/dimm_devs.c:515
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff818117c0-ffffffff818117d7: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81820e49)
Location: drivers/nvdimm/dimm_devs.c:645
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff81820680-ffffffff81820697: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81804149)
Location: drivers/nvdimm/dimm_devs.c:645
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff81803960-ffffffff81803977: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e819)
Location: drivers/nvdimm/dimm_devs.c:663
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff8188e2f0-ffffffff8188e307: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7e8b)
Location: drivers/nvdimm/dimm_devs.c:644
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff819d7980-ffffffff819d799d: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52d1b)
Location: drivers/nvdimm/dimm_devs.c:654
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff81b527d0-ffffffff81b527ed: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba61d0)
Location: drivers/nvdimm/dimm_devs.c:654
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff81ba5c90-ffffffff81ba5cad: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa450)
Location: drivers/nvdimm/dimm_devs.c:656
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff81bf9f10-ffffffff81bf9f2d: shutdown_security_notify (STB_LOCAL)
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
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffff8000109533e0)
Location: drivers/nvdimm/dimm_devs.c:508
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffff8000109533e0-ffff80001095340c: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (c000000000a00a10)
Location: drivers/nvdimm/dimm_devs.c:508
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
c000000000a00a10-c000000000a00a48: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c2d94)
Location: drivers/nvdimm/dimm_devs.c:508
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffe0005c2d94-ffffffe0005c2dc0: shutdown_security_notify (STB_LOCAL)
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
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81707390)
Location: drivers/nvdimm/dimm_devs.c:508
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff81707390-ffffffff817073a7: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816dae10)
Location: drivers/nvdimm/dimm_devs.c:508
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff816dae10-ffffffff816dae27: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81746160)
Location: drivers/nvdimm/dimm_devs.c:508
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff81746160-ffffffff81746177: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void shutdown_security_notify(void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff817615a0)
Location: drivers/nvdimm/dimm_devs.c:508
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nvdimm_security_setup_events
```
**Symbols:**

```
ffffffff817615a0-ffffffff817615b7: shutdown_security_notify (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
