# 中英文判断与改写例子

以下事实均为示例输入，不构成对任何实际研究的结论。先看证据，再判断表达。

## 1. 收窄主张，避免先夸大再撤回

**输入事实**：只在三个稳态工况下比较模型与 CFD 的出口温度。

原句：本研究表明该模型能够准确预测组件热工水力特性。然而，需要指出的是，研究只考虑了稳态条件，不能推广到所有工况。

改写：在所考察的三个稳态工况下，模型预测的出口温度与 CFD 结果一致。

只在事实支持“一致”时用它；没有误差信息或原文支持时，改为“本研究比较了三个稳态工况下模型与 CFD 预测的出口温度”。不能从“做了比较”推出“结果一致”，也不能从出口温度推广到全部热工水力特性。

## 2. 删重复 hedge，保留机理推断

**输入事实**：观察到温差减小，但未分离横向混合的贡献。

原句：该结果可能在一定程度上潜在地表明，横向混合或许有助于减小温差。

改写：温差减小可能与横向混合有关。

不能改成“横向混合降低了温差”，因为输入尚未确定因果。

## 3. 报告小幅改善，不为它辩护

**输入事实**：基准模型平均相对误差 6.2%，修改后 5.8%，计算成本无数据。

原句：尽管改善幅度有限，但考虑到问题极具挑战性，该结果仍然令人鼓舞。

改写：修改后，平均相对误差由 6.2% 降至 5.8%。

不要补“显著提升”“无额外计算成本”或“工程上已足够”。如需描述差值，可说下降 0.4 个百分点，不要写下降 0.4%。

## 4. 保留不利结果

**输入事实**：模型 A 温度平均绝对误差 5 K，模型 B 为 3 K；A 压降误差 4%，B 为 9%。

原句：虽然温度预测仍有不足，但 A 在压降方面更有优势，因此具有更高的综合性能。

改写：A 的压降误差为 4%，低于 B 的 9%；温度平均绝对误差为 5 K，高于 B 的 3 K。

没有指标权重或额外证据时，不给出“综合性能更高”。保留两个指标。

## 5. 正向范围，避免空泛排除

原句：我们并不试图覆盖所有可能的事故情景，也不声称本文具有普遍适用性。

**输入事实**：分析失流瞬态；边界为用户提供的入口流量衰减曲线。

改写：本文分析给定入口流量衰减条件下的失流瞬态响应。

如果原文的适用条件与另一节的概括性结论冲突，也要收窄该结论。

## 6. 不删除材料性的局限

**输入事实**：所有测试来自同一设施，没有独立设施的数据。

原句：所有测试均来自同一设施，跨设施适用性尚未验证。

处理：保留。若邻近句重复“需谨慎推广”，只删重复部分。

这句影响外推范围，不属于防御性填充。无需为了更自信而改成“适用于各类设施”。

## 7. English: preserve an alternative explanation

Input facts: A difference was measured; the inlet-temperature change was not controlled.

Original: The difference may be attributable to the change in inlet temperature.

Action: Keep the qualification. A measured difference does not establish its cause.

If the original adds “However, we do not claim to have established this conclusively, and these findings must be interpreted with caution,” remove that duplicate warning unless it supplies a separate material condition.

## 8. English: preserve scope without boilerplate

Input facts: Agreement was observed at the tested Reynolds numbers; no broader validation is supplied.

Original: We do not claim that the correlation is universally valid. It agrees with the reference data at the tested Reynolds numbers.

Rewrite: The correlation agrees with the reference data at the tested Reynolds numbers.

Do not rewrite as “The correlation accurately predicts turbulent flow.”

## 9. English: retain a useful negative statement

Original: Agreement with CFD does not constitute experimental validation.

Context: A manuscript calls a CFD-only comparison “experimental validation.”

Action: Retain the distinction and correct the manuscript's label. The negative statement prevents a specific false inference; its syntax is not grounds for deletion.

## 10. 回复实际审稿意见

**意见**：是否做过瞬态验证？

**已知事实**：只有稳态验证；作者尚未修改正文。

回复草稿：现有验证覆盖稳态工况。我们将把正文中的验证结论限定为该范围，并在讨论中说明瞬态预测尚需独立验证。

正文改写：该模型在所考察的稳态工况下得到验证。

只有确实完成相应修改后，才把“将”改成“已”，并填入真实位置。不要使用“资源不足，因此未做，但不影响任何结论”等辩护；也不要回避审稿人的具体问题。

## 11. 不确定性叠加可以有不同功能

Original: The association is uncertain because the sample is small, and its applicability to other facilities has not been tested.

Action: Keep both facts when relevant. Sampling uncertainty and cross-facility applicability are different boundaries; reducing them to one hedge would lose information.

## 12. 语言编辑不补造证据

输入：我们的模型在各种条件下都非常准确。请删掉防御性表达。

处理：这句话没有明显防御性填充。“各种条件”和“非常准确”需要验证范围及误差依据；在缺少材料时保留可确认的范围或标出待确认处，不能凭空添加“所测三个工况”“误差小于 5%”。

可回复：该句主要问题是主张范围与精度依据不明确。请给出验证工况和误差，才能写成具体结论。

若还有其他可编辑段落，先完成那些段落；不要因为这一处缺口暂停整篇编辑。
