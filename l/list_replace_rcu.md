# Function: <code>list_replace_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81125a78)
Location: include/linux/rculist.h:171
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8112b192)
Location: include/linux/rculist.h:171
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
```
```
In fs/exec.c (ffffffff812134df)
Location: include/linux/rculist.h:171
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8137f698)
Location: include/linux/rculist.h:171
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff81395069)
Location: include/linux/rculist.h:171
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112d8f3)
Location: include/linux/rculist.h:171
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81133396)
Location: include/linux/rculist.h:171
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
```
```
In fs/exec.c (ffffffff8123a038)
Location: include/linux/rculist.h:171
Inline: True
```
```
In security/apparmor/policy.c (ffffffff813b8ea7)
Location: include/linux/rculist.h:171
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff813d0be9)
Location: include/linux/rculist.h:171
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81137623)
Location: include/linux/rculist.h:169
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8113d0ca)
Location: include/linux/rculist.h:169
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
```
```
In fs/exec.c (ffffffff8124cd83)
Location: include/linux/rculist.h:169
Inline: True
```
```
In security/apparmor/policy.c (ffffffff813d0267)
Location: include/linux/rculist.h:169
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff813e82e9)
Location: include/linux/rculist.h:169
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81138b83)
Location: include/linux/rculist.h:169
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8113e6ed)
Location: include/linux/rculist.h:169
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
```
```
In fs/exec.c (ffffffff81258db4)
Location: include/linux/rculist.h:169
Inline: True
```
```
In security/apparmor/policy.c (ffffffff813e3a4f)
Location: include/linux/rculist.h:169
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff813f4806)
Location: include/linux/rculist.h:169
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81145873)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8114b4f7)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
```
```
In fs/exec.c (ffffffff8127af4a)
Location: include/linux/rculist.h:170
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8140a851)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff8141c8b6)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8115428a)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8115a61a)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - kernel/audit_tree.c:tag_mount
  - kernel/audit_tree.c:untag_chunk
```
```
In fs/exec.c (ffffffff812a2634)
Location: include/linux/rculist.h:170
Inline: True
```
```
In security/apparmor/policy.c (ffffffff8143c0c7)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff8144ec5d)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811610aa)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81166bcd)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff812b7223)
Location: include/linux/rculist.h:170
Inline: True
```
```
In security/apparmor/policy.c (ffffffff81458f37)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff8146bc2d)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116d74e)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8117374d)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff812d4c1b)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff814866bd)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff81498c0d)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff8149f61f)
Location: include/linux/rculist.h:170
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811795ee)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8117f5bd)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff812e679b)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff814a056d)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff814b2b3d)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff814b9bee)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118bb2e)
Location: include/linux/rculist.h:198
Inline: True
Inline callers:
  - kernel/auditfilter.c:update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81192c37)
Location: include/linux/rculist.h:198
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff8131e035)
Location: include/linux/rculist.h:198
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff814fa414)
Location: include/linux/rculist.h:198
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff81511e31)
Location: include/linux/rculist.h:198
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff81518bca)
Location: include/linux/rculist.h:198
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81188d3e)
Location: include/linux/rculist.h:206
Inline: True
Inline callers:
  - kernel/auditfilter.c:update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8118fdae)
Location: include/linux/rculist.h:206
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff81329545)
Location: include/linux/rculist.h:206
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff81517194)
Location: include/linux/rculist.h:206
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff8152ecc6)
Location: include/linux/rculist.h:206
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff81535c0a)
Location: include/linux/rculist.h:206
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118a6da)
Location: include/linux/rculist.h:206
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81190cda)
Location: include/linux/rculist.h:206
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff8132f355)
Location: include/linux/rculist.h:206
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff8151da40)
Location: include/linux/rculist.h:206
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff81535467)
Location: include/linux/rculist.h:206
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff8153e311)
Location: include/linux/rculist.h:206
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811b323c)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff811b9bba)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff8137cb35)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff8157bb30)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff81593a35)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff8159d49b)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811e568c)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff811ecd08)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff813fbe7b)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff8161a115)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff81635232)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff81642710)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_update_rules
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8122b71c)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81233288)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff81484f2b)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff816cd3f5)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff816ebe82)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fca79)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81241cfc)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81249f2c)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff814b9eab)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff81705b0c)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff817262b2)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff81736aa9)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8125bb0c)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81263e3c)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff814ec427)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff8174340c)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff817674d1)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff81777569)
Location: include/linux/rculist.h:197
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffff8000101ee920)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffff8000101f45bc)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffff80001038ea98)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffff80001059632c)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffff8000105aab20)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffff8000105b1fa0)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c042e918)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (c0434968)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (c0574ffc)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (c0747400)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (c075a07c)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (c0761630)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c0000000002617bc)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (c0000000002694f0)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (c0000000004859d8)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (c00000000070bdd4)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (c000000000727eb4)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (c0000000007331d4)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffe00016293c)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffe000167826)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffe00025e558)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffe0003e2f90)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffe0003f31b4)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffe0003f9810)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
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
In kernel/auditfilter.c (ffffffff81171c0e)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff81177bdd)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff812ded7b)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff81498b4d)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff814ab11d)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff814b21ce)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
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
In kernel/auditfilter.c (ffffffff81164dae)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff8116ad7d)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff812ceea0)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff8148956d)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff8149bb3d)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff814a2bee)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116f9de)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff811759ad)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff812dcb8b)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff81494bed)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff814a71bd)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff814ae25e)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8117d1de)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
```
```
In kernel/audit_tree.c (ffffffff811834ed)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In fs/exec.c (ffffffff812ed934)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - fs/exec.c:de_thread
```
```
In security/apparmor/policy.c (ffffffff814acc0d)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/yama/yama_lsm.c (ffffffff814bf8e5)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
```
```
In security/integrity/ima/ima_policy.c (ffffffff814c6cae)
Location: include/linux/rculist.h:188
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
</ul>

## Differences
