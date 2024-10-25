# What is Excel layouts for Business Central?
Business Central 2022 release wave 1 (version 20) introduced the feature _Excel layouts_ as a way to layout and run reports using Excel.

# What resources can I find in aka.ms/bcexcelsamples?
This repo contains instructions for how you can use different Excel and Power Query features in Excel layouts. The repo also have guidance on things you might want to do in a Excel report once it has been generated.

# FAQ
Please visit the [FAQ page](FAQ.md) for any questions on how to get started.

# Design guidelines
Please visit the [Design guidelines](./guidelines/README.md) for guidance on how to design good datasets and layouts.

# Example layout (Customer Sales List)

The Customer Sales List layout (available here: [Examples](./layouts%20(ready%20to%20use)) ) showcases a number of techniques that you might want to explore for your own layouts

1. The two worksheets _Sales by Customer_ and _Customer Sales by Location_ show how you can use combine a pivot table with slicers and charts to create simple, yet effective interactive reports. Note that you can edit header texts in the pivot table. The _Customer Sales by Location_ sheet show an important learning: add fixed size visuals (the slicers and charts) above dynamic size visuals (the pivot table) so that the report stil work with different data distributions. 
1. The worksheet _Customer Mailing List_ showcase how you can use table formulas in Excel to create calculated columns. See the [FAQ page](FAQ.md) for more information on table formulas in Excel.
1. The worksheet _Customers and credit_ showcase the use of Power Query in a layout. Navigate to Data, Get Data, Launch Power Query Editor. Now click on the _Credit score_ query and click _Advanced Editor_. What you see here is a M query (which is the programming language used in Power Query). Don't let this scare you, you rarely need to edit the raw M code. Note that on the first line, you can see where data is located (in the example, it is an Excel workbook stored on a Sharepoint site). You can use Power Query to read almost any kind of data you can imagine and merge/join this to the report dataset generated by Business Central. See the [FAQ page](FAQ.md) for more information on how to use Power Query in Excel.

# Example layout (multi-language layout for Customer Sales List)

The Customer Sales List multi-language layout (available here: [Examples](./layouts%20(ready%20to%20use)) ) showcases a number of techniques that you might want to explore for your own layouts

1. How to translate worksheet names
1. How to translate chart titles
1. How to translate pivot table elements
1. How you can use various static and runtime metadata from the *Aggregated Metadata* worksheet 


# Disclaimer
Microsoft Corporation (“Microsoft”) grants you a nonexclusive, perpetual, royalty-free right to use and modify the software code provided by us for the purposes of illustration  ("Sample Code") and to reproduce and distribute the object code form of the Sample Code, provided that you agree: (i) to not use our name, logo, or trademarks to market your software product in which the Sample Code is embedded; (ii) to include a valid copyright notice on your software product in which the Sample Code is embedded; and (iii) to indemnify, hold harmless, and defend us and our suppliers from and against any claims or lawsuits, whether in an action of contract, tort or otherwise, including attorneys’ fees, that arise or result from the use or distribution of the Sample Code or the use or other dealings in the Sample Code. Unless applicable law gives you more rights, Microsoft reserves all other rights not expressly granted herein, whether by implication, estoppel or otherwise. 

THE SAMPLE CODE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL MICROSOFT OR ITS LICENSORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THE SAMPLE CODE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DA MAGE.
