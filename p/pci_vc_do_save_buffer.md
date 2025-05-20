# Function: <code>pci_vc_do_save_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff81440ca0)
Location: drivers/pci/vc.c:186
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
```
**Symbols:**

```
ffffffff81440ca0-ffffffff8144138d: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff8148cbc0)
Location: drivers/pci/vc.c:186
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff8148cbc0-ffffffff8148d297: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff814ae3b0)
Location: drivers/pci/vc.c:186
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff814ae3b0-ffffffff814aea87: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff814b8730)
Location: drivers/pci/vc.c:186
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff814b8730-ffffffff814b8de9: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff814f8b80)
Location: drivers/pci/vc.c:186
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff814f8b80-ffffffff814f9239: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff815296f0)
Location: drivers/pci/vc.c:183
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff815296f0-ffffffff81529d0b: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff8153f5a0)
Location: drivers/pci/vc.c:183
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff8153f5a0-ffffffff8153fbb8: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:183
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff8156ee50-ffffffff8156f40d: pci_vc_do_save_buffer (STB_LOCAL)
ffffffff8156f565-ffffffff8156f61d: pci_vc_do_save_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:185
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff8158fe70-ffffffff81590449: pci_vc_do_save_buffer (STB_LOCAL)
ffffffff815905a5-ffffffff8159065d: pci_vc_do_save_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:185
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff81637b10-ffffffff81637f75: pci_vc_do_save_buffer (STB_LOCAL)
ffffffff81638147-ffffffff8163819e: pci_vc_do_save_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:184
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff8165c4d0-ffffffff8165c935: pci_vc_do_save_buffer (STB_LOCAL)
ffffffff81bf8db2-ffffffff81bf8e09: pci_vc_do_save_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:184
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff8163ea80-ffffffff8163eed4: pci_vc_do_save_buffer (STB_LOCAL)
ffffffff81beac09-ffffffff81beac60: pci_vc_do_save_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:184
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff816af610-ffffffff816afa61: pci_vc_do_save_buffer (STB_LOCAL)
ffffffff81ce5a9f-ffffffff81ce5af6: pci_vc_do_save_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:184
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff817d2ae0-ffffffff817d2f8f: pci_vc_do_save_buffer (STB_LOCAL)
ffffffff81eac563-ffffffff81eac5bf: pci_vc_do_save_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff818f33e0)
Location: drivers/pci/vc.c:184
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff818f33e0-ffffffff818f38db: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff81936810)
Location: drivers/pci/vc.c:184
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff81936810-ffffffff81936d2d: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff8197f670)
Location: drivers/pci/vc.c:185
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff8197f670-ffffffff8197fb8d: pci_vc_do_save_buffer (STB_LOCAL)
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
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffff8000106f4fe0)
Location: drivers/pci/vc.c:185
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffff8000106f4fe0-ffff8000106f55b0: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (c088fa6c)
Location: drivers/pci/vc.c:185
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
c088fa6c-c0890090: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (c0000000008739a0)
Location: drivers/pci/vc.c:185
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
c0000000008739a0-c0000000008741c4: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffe0004c7f2e)
Location: drivers/pci/vc.c:185
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffe0004c7f2e-ffffffe0004c84d4: pci_vc_do_save_buffer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:185
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff81583cf0-ffffffff815842c9: pci_vc_do_save_buffer (STB_LOCAL)
ffffffff81584425-ffffffff815844dd: pci_vc_do_save_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:185
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff81572ad0-ffffffff815730a9: pci_vc_do_save_buffer (STB_LOCAL)
ffffffff81573205-ffffffff815732bd: pci_vc_do_save_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:185
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff81583bc0-ffffffff81584199: pci_vc_do_save_buffer (STB_LOCAL)
ffffffff815842f5-ffffffff815843ad: pci_vc_do_save_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_vc_do_save_buffer(struct pci_dev *dev, int pos, struct pci_cap_saved_state *save_state, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:185
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_allocate_vc_save_buffers
  - drivers/pci/vc.c:pci_restore_vc_state
  - drivers/pci/vc.c:pci_save_vc_state
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff8159e070-ffffffff8159e649: pci_vc_do_save_buffer (STB_LOCAL)
ffffffff8159e7a5-ffffffff8159e85d: pci_vc_do_save_buffer.cold (STB_LOCAL)
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
