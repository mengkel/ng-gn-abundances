# ng-gn-abundances
This is a detailed description of r-process ng-gn equilibrium phase isotopic abundances calculation. If you would like to see our simple model, you can run this notebook on [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1csQ2-oSmTEoqS62X8BxfTV4_DV5c45G8?usp=sharing). Another available source for running those files without a google account is [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mengkel/ng-gn-abundances/HEAD)

If you would like to see the isotopic abundances distribution computed from the neutron separation energy (REACLIB 2.0 datatbase), you can run the notebook plot_ng_abunds_with_sn_data.ipynb or you can run  this on [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1FZix6Pcqqs78I1c1ylHUp2-Cxi85a9hp?usp=sharing)

# pg-gp-abundances
plot_pg_abunds_model.ipynb file describes the isotonic abundances distribution in pg-gp equilibrium phase in $\nu$p process which happens in the inner ejected layer of the core-collapse supernova.[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1aTKbH05x2XmtJlJ9vbfrE17Py2Pe6k8l/view?usp=sharing)

If you would like to see the isotonic abundances distribution computed from the proton separation energy (REACLIB 2.0 datatbase), you can run the notebook plot_pg_abunds_with_sp_data.ipynb or you can run  this on [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1P1Sio6Rfs_9aqMVqDLmJNUpp5Vg1rQbJ/view?usp=sharing)

# isotoxic abundances via linear Sn + epsilon
plot_linear_sn_plus_epsilon.ipynb computes the isotoxic (x = p or n) abundances via a linear Sn and a spike function which is called epsilon. This files ahows that all of the Sn distribution can be regarded as linear Sn and a spike function. You can also define your own epsilon function to see how the abundance curve transfers from a Gaussian to your curve. You can also run this file on [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17hBxrrAgcUtaGdCZFO1DYH7aKG3D3AX9?usp=sharing) 

# r-process path movement
We define the r-process path in this way: at any given time, for each element with proton number Z, there is an isotope with maximum abundance; the collection of all such isotopes forms the path at that time. r-path-motion-new.ipynb shows the movement of the r process path when the temperature drops and the neutron number density decreases. In our model, we used the model data(Yn and T_9). If anyone needs to test their own trajactory data, they can input their data in this file. The instructions are inside this notebook. You can also run this file on [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1--E5flBJQXmYvPqU0J5KWsX1SZTwg6BW)  

