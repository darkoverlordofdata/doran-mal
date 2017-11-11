cmake_minimum_required ( VERSION 3.1 )
#########################################################################################
#
#   Library: MersenneTwister
#
#########################################################################################
project ( mt19937 VERSION 0.1.0 )

set ( VALAC_OPTIONS "${VALAC_OPTIONS};--vapidir=${CMAKE_SOURCE_DIR}/.lib/mal/vapis" PARENT_SCOPE)
