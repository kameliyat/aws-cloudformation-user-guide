# AWS::WAFv2::WebACL RuleAction<a name="aws-properties-wafv2-webacl-ruleaction"></a>

**Note**  
This is the latest version of **AWS WAF**, named AWS WAFV2, released in November, 2019\. For information, including how to migrate your AWS WAF resources from the prior release, see the [AWS WAF Developer Guide](https://docs.aws.amazon.com/waf/latest/developerguide/waf-chapter.html)\. 

The action that AWS WAF should take on a web request when it matches a rule's statement\. Settings at the web ACL level can override the rule action setting\. 

## Syntax<a name="aws-properties-wafv2-webacl-ruleaction-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-wafv2-webacl-ruleaction-syntax.json"></a>

```
{
  "[Allow](#cfn-wafv2-webacl-ruleaction-allow)" : [AllowAction](aws-properties-wafv2-webacl-allowaction.md),
  "[Block](#cfn-wafv2-webacl-ruleaction-block)" : [BlockAction](aws-properties-wafv2-webacl-blockaction.md),
  "[Count](#cfn-wafv2-webacl-ruleaction-count)" : [CountAction](aws-properties-wafv2-webacl-countaction.md)
}
```

### YAML<a name="aws-properties-wafv2-webacl-ruleaction-syntax.yaml"></a>

```
  [Allow](#cfn-wafv2-webacl-ruleaction-allow): 
    [AllowAction](aws-properties-wafv2-webacl-allowaction.md)
  [Block](#cfn-wafv2-webacl-ruleaction-block): 
    [BlockAction](aws-properties-wafv2-webacl-blockaction.md)
  [Count](#cfn-wafv2-webacl-ruleaction-count): 
    [CountAction](aws-properties-wafv2-webacl-countaction.md)
```

## Properties<a name="aws-properties-wafv2-webacl-ruleaction-properties"></a>

`Allow`  <a name="cfn-wafv2-webacl-ruleaction-allow"></a>
Instructs AWS WAF to allow the web request\.  
*Required*: No  
*Type*: [AllowAction](aws-properties-wafv2-webacl-allowaction.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`Block`  <a name="cfn-wafv2-webacl-ruleaction-block"></a>
Instructs AWS WAF to block the web request\.  
*Required*: No  
*Type*: [BlockAction](aws-properties-wafv2-webacl-blockaction.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`Count`  <a name="cfn-wafv2-webacl-ruleaction-count"></a>
Instructs AWS WAF to count the web request and allow it\.  
*Required*: No  
*Type*: [CountAction](aws-properties-wafv2-webacl-countaction.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)