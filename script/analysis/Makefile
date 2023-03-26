#Makefile by AK . Using Python 3.8.12


#editted to remove plot for TpTe and editted the print statements to have (). Both due to errors.
movie_2d:
	python movie_2d.py ${HOME}/disk_wind/dumps/

movie:
	python movie.py ${HOME}/disk_wind/dumps/ RHO

snap:
	python snap.py ${HOME}/disk_wind/dumps/dump2d_00000108.h5 PRESS

# Copied util.py from nubhlight/script to nubhlight/script/analysis
# Editted hdf5_to_dict.py to have
# if len(dfiles) < 1: dfiles = sorted(glob.glob(os.path.join(path,'dump*.h5')))
snap_diag:
	python snap_diag.py ${HOME}/disk_wind/dumps/

# Diag and diag_summary not working.
diag :
	python diag.py ${HOME}/disk_wind/dumps/

diag_summary:
	python diag_summary.py ${HOME}/disk_wind/dumps/ fluid


#missing `import util`


## cd ${HOME}/disk_wind/nubhlight/script/analysis

## List of variables: RHO UU U1 U2 U3 B1 B2 B3 Ye Ye_em ATM divb fail_save Nsph nph Nem Nabs Nsc tau_cool dtau_scatt dtau_tot PRESS TEMP ENT Theta THETA Thetae tau_heat Qrad Nem_e Nem_anti Nem_x Nabs_e Nabs_anti Nabs_x bsq beta ut uX1 uX2 uX3 j2 ur betar Jem Jabs Jsc dtau_abs dtau_dens dlepton_rad dyedt_rad
## List of modes : fluid, rad, perf


