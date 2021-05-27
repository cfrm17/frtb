# FRTB Standardized Approach

The Fundamental Review of the Trading Book (FRTB) is a new Basel committee framework for the next generation market risk regulatory capital rules. It is inspired by the undercapitalisation of trading book exposures witnessed during the financial crisis. FRTB aims to address shortcoming of the current Basel 2.5 market risk capital framework.

FRTB provides a clear definition of the boundary between the trading book and the banking book. It consists of an overhaul of the internal model approach (IMA) to focus on tail risk and an overhaul of the standardized approach (SA) to make it more risk sensitive. Each approach also explicitly captures default risk and other residual risks. Liquidity risk is explicitly included for different asset classes via liquidity horizons. This presentation provides an overview of the standardised approach. 

Keywords:
Fundamental Review of the Trading Book,  FRTB, standardized approach, internal model approach, Sensitivity-based risk charge, Default risk charge, Residual add-on


	FRTB definition
	The Fundamental Review of the Trading Book (FRTB) is a new Basel committee framework for the next generation market risk regulatory capital rules.
	FRTB is inspired by the undercapitalisation of trading book exposures witnessed during the financial crisis
	It aims to address shortcoming of the current Basel 2.5 market risk capital framework

	FRTB vs Basel 2.5

	Standardised Approach
	FRTB
Sensitivity based risk charge + Default risk charge + Residual risk add-on
	Basel 2.5
Standardised capital charge
	Internal Model Approach
	FRTB
Expected shortfall + Default risk charge + Non-modellable risk factors
	Basel 2.5
VaR + Stress VaR + Incremental Risk Charge (IRC)


	FRTB main features
	Clear definition of the boundary between the trading book and the banking book
	An overhaul of the internal model approach (IMA) to focus on tail risk
	An overhaul of the standardized approach (sa) to make it more risk sensitive and explicitly capture default risk and other residual risks
	Inclusion of liquidity horizons explicitly for different asset classes.


	FRTB approaches
	Standardized approach (SA): a regulator-set approach
	Sensitivity-based risk charge (SBRC)
	Default risk charge (DRC-SA)
	Residual add-on (RAD)
	Internal model approach (IMA): a bank’s own approach
	Expected shortfall (ES)
	Default risk charge (DRC-IMA)
	Non-modellable risk factors (NMRF)
This presentation focuses on standardized approach


	FRTB Standardized Approach
	3 risk measures: Delta, Vega and Curvature
	7 risk classes:
	General interest rate (GII)
	Credit spread risk
	Credit spread risk: non-correlated securitisation
	Credit spread risk: correlated securitisation
	Equity
	Commodity
	Foreign exchange
	Sensitivity based risk charge should be calculated separately for each risk class and each risk measure
	Reporting hierarchy: portfolio, desk, bank
	Total risk charge
Total = sensitivity-based risk charge + default risk charge +residual add-on
For example, an equity desk has only equity and interest rate risk,
Total risk charge = equity Delta charge + equity Vega charge + equity Curvature charge + GII charge + DRC + RAD



	FRTB Sensitivity Based Risk Charge
	Sensitivities required
	Delta: the first order derivative with respect to underlying price
	Vega: the first order derivative with respect to implied volatility
	Curvature: equivalent to the sum of all high-order derivatives with respect to underlying price
	Sensitivity note
	All trading products have Delta
	Only non-linear products (e.g., options) have Vega and Curvature
	Sensitivity calculation
	Regulator clearly defines all Delta and Curvature calculation but not Vega
	Interest rate deltas are computed on yield rates (or zero coupon rates) rather than instrument quotes (e.g., swap rates, futures)
	Curvature is a new measurement that is equal to value change minus Delta
	Bucket and risk factor
	Sensitivities should be divided into buckets and risk factors within each risk measure and each risk class
	Risk weight: Basel defines a risk weight for each risk factor
	Risk correlation: Basel defines correlations between risk factor and between buckets
	Calculation
	Sum all sensitivities belonging to the same risk factor and then multiply by risk weight  risk charge
	
	 W_i S_i 
	
	per risk factor
	Within one bucket, two risk factor charges can be added as
	
K_b=√(〖(W_i S_i)〗^2+〖(W_j S_j)〗^2+ρ_ij W_i S_i)(W_i S_i))

	Within each class and each measure, two bucket charges can be added as (for example, the GII Delta only has two bucket.

GII Delta=√(K_b^2+K_c^2+γ_bc K_b^2 K_c^2 )


	FRTB Default risk charge
	Scope
	Debt instruments
	Equity products
	Securitisation
	Calculation procedure
	Determine jump-to-default (JTD) loss amount
	Offset the JTD amounts of long and short exposures with respect to the same obligor
	Discount the net short exposures by a hedge benefit ratio
	Apply default risk weights to exposures to arrive at the DRC


	FRTB Residual add-on
	The following trade types bearing residual risk
	Traded in incomplete markets
	Gap risk: such as path dependent options (barrier, Asian, digital, Bermudan, etc.)
	Correlation risk: such as multiple underlying options (basket, best, spread, basis, quote, etc.)
	Behavioural risk: such as mortgage
	Calculation
	RAD = notional * factor (1% or 0.1%) 




References:

https://finpricing.com/lib/EqSwap.html

https://bitbucket.org/cfrm17/frtb/downloads/frtbSa-6.pdf

