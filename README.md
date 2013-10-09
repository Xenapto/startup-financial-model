Getting started
===============

See the *Instructions* section below.

Note on this GitHub repository
==============================

The spreadsheet you can find here is the awesome Template Startup Financial Model developed by David Teten and associates. You can read more about the model from their cover notes which I reproduce below (see *Template Startup Financial Model*).

Contributing
------------
I hope by putting this repository here that people who find this useful will contribute their own enhancements to this model. If you fork this repository and create a generally-useful modification please submit a pull request and I'll add it back into the master branch.

Adding a locale
---------------

1.  To add a locale, e.g. `fr-FR`, copy an existing locale worksheet to a new worksheet named `fr-FR`
1.  Amend the yellow cells to suit your new locale
1.  In the taxation fields, the tax on corporate profits is your locale's tax on the startup's gross income.
1.  The taxation rate for employers' contributions to payroll taxes is the amount the employer pays in addition to deducting income tax and other taxes from the employe''s gross salary. In other words, you can enter the actual gross salary in the model worksheet and any additional payroll costs are added according to this rate. An example of this is Employers' Class 1 National Insurance contributions in the UK. An employee earning £100,000 would cost the employer £113,800 once the employers' National Insurance contributions are added.

License
-------
This template financial model was downloaded from [David Teten's website](http://teten.com/blog/2011/11/10/template-startup-financial-model/ "Template Startup Financial Model") under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 United States license which covers his entire site. I've included a screenshot of the site on October 8th 2013 in case the license is changed at any point.

I've given this repository an MIT License which similarly requires you to maintain the attribution of the original work to David Teten. It would be polite also to mention the work of Rodi Blokh.


Template Startup Financial Model
================================

About
-----
We developed this model as a simple end-to-end financial model for an early-stage startup, although it is useful to anyone building a model for a company.  The model outputs standard financial statements and key operating metrics based on a wide range of user inputs, and is highly customizable and entirely transparent.

Credits
-------
This model was developed by Rodi Blokh in association with ff Venture Capital (www.ffvc.com) based on a sanitized version of a financial model developed by David Teten (www.teten.com) for the startups he has run.  Rodi is a Berkeley MBA student (Haas MBA '13) and former corporate banker at Bank of America Merrill Lynch (rblokh@gmail.com).  David is a Partner at ff Venture Capital, Chair of Harvard Business School Angels of Greater New York, and former Bear Stearns investment banker (info@teten.com).  Thank you to Adam Kalamchi (Columbia MBA ’13) for some initial input on this model.

If you have feedback on the model, contact info@teten.com .  We are very interested in suggested additional improvements and will try to reflect them.  However, we cannot  provide you with user support.

Instructions
------------
Click on the "Model", "Valuation" and "Funding Rounds" tabs and input relevant data.  All input cells are highlighted yellow with blue-colored text.

To add personnel, add additional rows in the Personnel Assumptions section.  Select the columns where an employee starts to correspond with personnel hiring timing.

The WACC section on the "Valuation" tab and the entire "Funding Rounds" tab is independent of the "Model" and requires independent inputs.
Non-input cells should not be altered by inexperienced users.  Cell A4 on the "Model" tab acts as a check of the model and will display an error message if the model logic is broken.  This error message tests for most, but definitely not all possible errors.

Model Logic
-----------
Revenues in the model are arbitrarily assumed to be based primarily on employee headcount.  However, this is certainly not an accurate approach for all ventures, and in fact as venture capitalists we prefer companies in which the correlation between headcount and revenues is very low.  A separate row labeled "Other Revenues" may be more relevant for modeling revenue projections for your particular company.
