TOP = ../../..
PELELMEX_HOME      ?= ${TOP}
AMREX_HOME         ?= ${PELELMEX_HOME}/Submodules/amrex
PELE_PHYSICS_HOME  ?= ${PELELMEX_HOME}/Submodules/PelePhysics
AMREX_HYDRO_HOME   ?= ${PELELMEX_HOME}/Submodules/AMReX-Hydro
HYPRE_HOME         = /ccs/home/lesclapez/hypre/install-2807

# AMReX
DIM             = 3
DEBUG           = FALSE
PRECISION       = DOUBLE
VERBOSE         = FALSE
TINY_PROFILE    = FALSE
USE_EB			 = TRUE
USE_HYPRE		 = FALSE

# Compilation
COMP            = clang
USE_MPI         = TRUE
USE_OMP         = FALSE
USE_CUDA        = FALSE
USE_HIP         = TRUE

# PeleLMeX
CEXE_headers 	+= EBUserDefined.H

PELE_USE_MAGMA  = TRUE

# PelePhysics
Chemistry_Model = dodecane_lu_qss
Eos_Model		 = Fuego
Transport_Model = Simple

include $(PELELMEX_HOME)/Utils/Make.PeleLMeX
